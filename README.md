# Evidence Desk

An interactive browser prototype exploring how human reviewers can check simulated AI suggestions about online claims.

## Project status

Case 001 shows a supported library closure claim incorrectly flagged by the simulated AI. Case 002 shows a broader campus closure claim incorrectly accepted even though the fictional notice applies only to North Hall. Reviewers can inspect evidence, accept or override a suggestion, defer judgement, record a reason, and compare the AI suggestion with the final decision.

Posts, notices and AI outputs are fictional and prewritten. No live AI model or fact-checking source is connected. The prototype does not measure real-world detection accuracy.

## Run

Open index.html in a browser. Follow its link to Case 002. No dependencies or API keys are required.

## Development and AI assistance

OpenAI Codex helped draft the initial HTML, CSS and JavaScript and prepare the report and README. I reviewed and revised the scenarios during development. I clarified that Case 001 only says the library closes at 6 pm; it does not claim the whole campus is closing, so it should not be described as a campus-wide exaggeration. I suggested a separate campus-closure case: the fictional post says the entire university will close, while the notice says only North Hall will close and its classes will move online. I asked for the simulated AI to make the wrong call by accepting the broader claim, so a reviewer could reject it after checking the notice. I checked that the result screen clearly shows the AI suggestion and the reviewer’s final decision. All claims, notices and AI responses are fixed fictional examples; no live AI model is connected.

## Live prototype

https://evidence-desk-library-review.luxelapis.chatgpt.site/
