# Name Badge

## Introduction @unplugged

Make yourself known with a fancy name badge powered by your @boardname@!

We will use this project to learn the key steps in wrting code to run on the @boardname@. You will:

1. **Code it**     - write your code in the MakeCode editor
2. **Test it**     - use the simulator to debug your code
3. **Connect it**  - attach your micro:bit to the PC with a USB cable
4. **Pair it**     - set up the communication link to the micro:bit  
5. **Download it** - send your code to the micro:bit
6. **Use it**      - check your code running on the micro:bit
7. **Save it**     - save your code to your student drive

## Step 1: Code @fullscreen

First, let's get your name to display on the screen.

From the ``||input:Input||`` Toolbox drawer, drag an ``||input:on button A pressed||`` block onto the Workspace.

```blocks
input.onButtonPressed(Button.A, function () {

})
```

## Step 2: Show a string @fullscreen

From the ``||basic:Basic||`` Toolbox drawer drag a ``||basic:show string||`` block into the ``||input:on button A pressed||`` block.

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showString("Hello!")
})
```

## Step 3: Show my name @fullscreen

In the ``||basic:show string||`` block, type your name.

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showString("My Name")
})
```

## Step 4: Test the badge @fullscreen

Go to the simulator and test your name badge by pressing button **A**.

```sim
input.onButtonPressed(Button.A, function () {
    basic.showString("My Name")
})
```

## Step 5: Download @unplugged

Congratulations on writing your first bit of code for the micro:bit. 

Now you need get your code onto the micro:bit and run it. Click the link below to load instructions on how to do that:

[Click here for Download and Save instructions](https://sites.google.com/view/belmontcodeclub/help/microbit)

Finally, you will need to click the `|Exit tutorial|` button to exit this tutorial so you can follow the Download and Save instructions.