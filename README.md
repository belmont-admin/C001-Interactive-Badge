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

## Button press 

From the ``||input:Input||`` Toolbox drawer, drag an ``||input:on button A pressed||`` block onto the Workspace.

```blocks
input.onButtonPressed(Button.A, function () {

})
```

## Show a string

From the ``||basic:Basic||`` Toolbox drawer drag a ``||basic:show string||`` block into the ``||input:on button A pressed||`` block.

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showString("Hello!")
})
```

## Show my name

In the ``||basic:show string||`` block, type your name.

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showString("My Name")
})
```

# Test the badge

Go to the simulator and test your name badge by pressing button **A**.

```sim
input.onButtonPressed(Button.A, function () {
    basic.showString("My Name")
})
```

# Download

Download the program to your @boardname@:

1. Make sure your @boardname@ is plugged into the computer.
![alt text](https://github.com/belmont-admin/C001-Interactive-Badge/raw/master/images/1-connect.jpg "Logo Title Text 1")

![](https://github.com/belmont-admin/C001-Interactive-Badge/raw/master/images/1-connect.jpg =100x)

2. Click the `|Download|` button.

