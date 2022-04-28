Followed the tutorial from https://developers.ceramic.network/tools/glaze/example/

How to clone and run:
1. `git clone git@github.com:pawartur/ceramic-simplenote-datamodel-scripts.git`
2. `cd ceramic-simplenote-datamodel-scripts`
3. `npm install`
4. `ceramic daemon`
5. Open another terminal and go to `ceramic-simplenote-datamodel-scripts` dir again
6. `glaze did:create`
7. Get the `seed` output from the previous step and set it as `DID_KEY` environmental variable
8. `node src/create-model.mjs`
9. `node --experimental-json-modules src/run.mjs`
10. If you see the note objects logged in the console, all is good :) 
