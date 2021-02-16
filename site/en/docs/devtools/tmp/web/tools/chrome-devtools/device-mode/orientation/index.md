---
layout: "layouts/doc-post.njk"
title: "Simulate Device Orientation With Chrome DevTools"
authors:
  - kaycebasques
date: 2018-12-18
updated: 2020-07-10
description: "Open the Sensors tab and go to the &#34;Orientation&#34; section."
---

To simulate different [device orientations][1] from Chrome DevTools:

1.  Press <kbd>Command</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> (Mac) or
    <kbd>Control</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> (Windows, Linux, Chrome OS) to open the
    **Command Menu**.

    ![The Command Menu.](/web/tools/chrome-devtools/images/shared/command-menu.png)

    **Figure 1**. The Command Menu

2.  Type `sensors`, select **Show Sensors**, and press <kbd>Enter</kbd>. The **Sensors** tab opens
    up at the bottom of your DevTools window.
3.  From the **Orientation** list select one of the preset orientations, like **Portrait upside
    down**, or select **Custom orientation** to provide your own exact orientation.

    ![Selecting 'Portrait upside down' from the 'Orientation' list.](/web/tools/chrome-devtools/device-mode/imgs/portrait-upside-down.png)

    **Figure 2**. Selecting **Portrait upside down** from the **Orientation** list

    After selecting **Custom orientation** the **alpha**, **beta**, and **gamma** fields are
    enabled. See [Alpha][2], [Beta][3], and [Gamma][4] to understand how these axes work.

    You can also set a custom orientation by dragging the **Orientation Model**. Hold
    <kbd>Shift</kbd> before dragging to rotate along the **alpha** axis.

    ![The Orientation Model.](/web/tools/chrome-devtools/device-mode/imgs/orientation-model.png)

    **Figure 3**. The **Orientation Model**

[1]: /web/fundamentals/native-hardware/device-orientation
[2]: /web/fundamentals/native-hardware/device-orientation#alpha
[3]: /web/fundamentals/native-hardware/device-orientation#beta
[4]: /web/fundamentals/native-hardware/device-orientation#gamma