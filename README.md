# Information

This is a collaborative exercism which has been revised a bit.

# Submitting Solution

## Downloading

First download the bowling project from exercism.io by running the command:

```
exercism download --exercise=bowling --track=javascript
```

This will create a new folder at "/Users/Exercism/javascript/bowling". Open this new 'bowling' folder inside of Visual Studio Code.

Now at this point, we need to download the code from this repository. Simply download this repository with the green button at the top right by either downloading as zip or copying the HTTPS or SSH link and using the command:

```
git clone <link-here>
```

Then once you have this code downloaded somewhere, copy the code inside of bowling.js from this repository to the bowling.js inside of your 'bowling' exercism folder.

Once you have made sure everything looks correct, go to the bowling.spec.js and make sure you enable all the tests by replacing all occurrences of "xtest" with "test". You may also simply copy the bowling.spec.js from this repository to the bowling.spec.js file in your exercism folder.

## Testing

Once you have everything set up from the previous setup, create a new terminal and run:

```
npm run test
```

This will run all of the tests provided by exercism for this project.
If you see in green text 30 passed near the bottom of the command, then the project is working correctly. Please make sure to review the code and research sections of the code you are not familiar with.

## Submitting

Once you are confident all the tests are passing, open a command line, and execute this command:

```
exercism submit bowling.js
```

This will submit your current code to exercism.

After completing this command, a link to your submission will be printed in the terminal.

You can do CTRL+CLICK on the link to open it with Visual Studio Code. It may prompt you if you are sure you want to go to this link. Simply confirm the dialog.

Once you reach the submission page, you may see on the right side a button labeled something similar to "Confirm your Submission". Pressing that and filling out the remaining prompts will complete your submission.

If you do not see a "Confirm your Submission" perhaps someone is reviewing your submission. Simply check back occasionally until you can submit.
