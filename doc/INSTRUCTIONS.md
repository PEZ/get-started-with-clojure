# How to use The Getting Started Project

The Getting Started Project consist of three Clojure files, which will serve as your interactive guides:

1. `hello_repl.clj` – The basics of how to evaluate code in Calva (i.e. using the REPL)
2. `hello_paredit.clj` - A super brief intro to Calva structural editing ([Paredit](https://calva.io/paredit))
3. `welcome_to_clojure.clj` - The very basics of the Clojure language

The files contain a mix of guiding text and snippets of code. You will use the REPL to evaluate the code and sometimes you will be asked to write some code and evaluate it. And so on.

## Let's go!

Fire up the Getting Started REPL:

0. Give the guides some space:
   * Maximize the browser window.
   * Close thee Explorer pane.
   * Shrink the Output/Terminal/Etc pane to about a third of what it is now.
1. Click the **REPL** button in the status bar

   ![VS Code Statusbar with Clojure REPL button](status-bar-repl-button.png)

   <details><summary>Don't see the REPL button?</summary>

    This could be because some firewall or adblocker prevents the downloading of the Calva extension. See [issue #9](https://github.com/PEZ/rich4clojure/issues/9) for more clues on this.

    </details>
1. Select **Start your project with a REPL and connect (a.k.a. Jack-in)** from the quick pick menu.

   ![The Calva REPL Menu](repl-menu.png)

The REPL will now start and connect, when it is done it should look like so:

![](get-started-with-clojure-window-layout.png)

If the `hello_repl.clj` tab is not active when the Calva output window has printed that the file is loaded, then activate the tab.

If things seem to work (it looks like the picture shows) you can close the Problems/Output/Terminal area (resize it to zero), to make more room for the guide content. Both the VS Code Output and Terminal panes can contain messages that is needed when you think something has gone wrong and want to ask/report about it.

Happy Interactve Programming! 🎉

## Learn and Practice Clojure using Rich 4Clojure

If you like the style of interactive learning that this guide provides, you should definitely check [Rich 4Clojure](https://github.com/PEZ/rich4clojure) out. It also can be used in the zero-installed way.

You can regard **Rich 4Clojure** as a companion to this guide. It is aimed at practicing Clojure, starting at the elementary levels, bringing you to advanced stuff.

<details><summary>Can I use Rich 4Clojure instead of this guide?</summary>

I suggest you start by opening up this guide and do the Calva part of the excerises. Then use the `welcome_to_clojure.clj` guide in combination with **Rich 4Clojure**.

</details>

## Learn more

The guides are sprinkled with URLs for the various topics brought up.

There are links to beginner resources at [calva.io/get-started-with-clojure](https://calva.io/get-started-with-clojure/).

The Calva Documentation is here: [calva.io](https://calva.io/).

