# Love Maths course source

[Português (Brasil)](README.pt-BR.md)

## Idea and process

Fork of Code-Institute-Solutions/love-maths-2.0-sourcecode. Reviewed on 2026-10-01. The numbered folders record a course sequence, not an original product history or evidence of personal authorship. Original material remains unchanged.

## Architecture and design

Folders cover basics, JavaScript, question/answer display, multiplication/subtraction, tidying and division. Each stage is a static lesson snapshot, not a single root application. The reviewed final stage is 06-division-challenge/index.html with assets/js/script.js. It binds operation/submit/Enter events, generates operands from 1 to 25, checks integer answers and updates DOM scores. Division multiplies the operands before dividing by the second to produce an integer answer. There is no backend or persistent score in this reviewed stage.

## Local preview

```bash
cd 06-division-challenge
python3 -m http.server 8000
```

Open localhost:8000. Do not run a root preview and expect a root index page. This command was not run during the update; no current public deployment was verified.

## Testing and limitations

No tests were run here. Verify each stage separately rather than treating earlier folders as the finished feature set. For the final stage, check four operations, Enter/button input, focus and scores, empty/decimal input and keyboard labels. parseInt truncates decimals and empty input becomes NaN. Course reference code is not a claim that all manual or automated checks pass.

## Snapshots

No new screenshot was verified or added. Future dated captures under docs/assets/ should name the stage and actual state shown, not imply original dashboard design. Preserve upstream assets and attribution.

## Credits and licensing

[Code Institute solution source](https://github.com/Code-Institute-Solutions/love-maths-2.0-sourcecode) and its assets retain their original rights. No license is added or replaced. The original README is preserved below.

---

## Original README

# Starter Maths Game

This maths game is used to teach the basics of JavaScript and the DOM.

## REQUIRED (TESTED):

* Add a division game that requires integers as answers

## BONUS (NOT TESTED):

* Provide better feedback to the user - we don't want to use `alert()`
* Add difficulty levels - Easy, Normal, Difficult - that affect the complexity of the questions

## SUPER BONUS (NOT TESTED):
* Add a countdown timer to the game
* Add a high-score chart for people who get the most answers right in the time available (research using local storage)
