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

## Step 5: Download @fullscreen

Download the program to your @boardname@:

1. Make sure your @boardname@ is plugged into the computer.
![alt text](https://github.com/belmont-admin/C001-Interactive-Badge/raw/master/images/1-connect.jpg "Connect it")

2. Click on the cogwheel icon and choose the 'Pair device' option
![alt text](https://github.com/belmont-admin/C001-Interactive-Badge/raw/master/images/2-pair.png "Pair it")

3. Click the `|Pair device|` button.
![alt text](https://github.com/belmont-admin/C001-Interactive-Badge/raw/master/images/3-pair-pop-up.png "Pair it")

4. In the pop up that appears click on the BBC micro:bit entry and the click the `|Connect|` button.
![alt text](https://github.com/belmont-admin/C001-Interactive-Badge/raw/master/images/4-connect.png "Pair it")
 "Pair it")

5. A **toast** message will appear briefly to confirm you are paired
![alt text](https://github.com/belmont-admin/C001-Interactive-Badge/raw/master/images/5-paired.png "Pair it")
 "Pair it")

6. Click the `|Download|` button to send your code to the micro:bit