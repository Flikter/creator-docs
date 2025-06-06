---
title: View tab
description: The View tab lets you toggle various windows in Studio and customize display options.
---

The **View** tab lets you toggle various windows in Studio, toggle the [view selector](#view-selector), and customize [display options](#display-options).

<img src="../assets/studio/general/Toolbar-View-Tab.png" width="876" alt="View tab indicated in Studio toolbar" />

## Windows and tools

<table>
<thead>
  <tr>
    <th>Option</th>
    <th>Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>**Explorer**</td>
    <td>Shows the [Explorer](../studio/explorer.md) window containing a hierarchical tree of the instances and services in the place.</td>
  </tr>
  <tr>
    <td>**Properties**</td>
    <td>Shows the [Properties](../studio/properties.md) window containing all properties of selected object(s).</td>
  </tr>
  <tr>
    <td>**Asset Manager**</td>
    <td>Toggles the [Asset Manager](../projects/assets/manager.md) window for managing the experience's places, images, meshes, and more.</td>
  </tr>
  <tr>
    <td>**Toolbox**</td>
    <td>Toggles the [Toolbox](../projects/assets/toolbox.md) window open and closed.</td>
  </tr>
  <tr>
    <td>**Output**</td>
    <td>The [Output](../studio/output.md) window shows any errors, warnings, or print outputs from running scripts.</td>
  </tr>
  <tr>
    <td>**Command Bar**</td>
    <td>The [Command Bar](../studio/ui-overview.md#command-bar) can be used to execute Luau code outside of scripts.</td>
  </tr>
	<tr>
    <td>**Find&nbsp;All&nbsp;/ Replace&nbsp;All**</td>
    <td>Displays the results from searching with <kbd>Ctrl</kbd><kbd>Shift</kbd><kbd>F</kbd> on Windows or <kbd>⌘</kbd><kbd>Shift</kbd><kbd>F</kbd> on macOS.</td>
  </tr>
	<tr>
    <td>**Terrain Editor**</td>
    <td>Opens a window with tools for [creating and shaping terrain](../studio/terrain-editor.md).</td>
  </tr>
	<tr>
    <td>**Tag Editor**</td>
    <td>Opens a window with tools for defining, assigning, and managing tags for use with `Class.CollectionService`.</td>
  </tr>
</tbody>
</table>

## View Selector

The **View Selector** widget lets you easily navigate between 14 views in 3D space to get the perfect view of your creations. Clicking on any face or corner of the selector moves the camera to that orientation. You can also click and drag the selector widget to reposition it anywhere in the 3D viewport.

<img src="../assets/studio/general/View-Tab-View-Selector.png" width="782" alt="View Selector tool selected in View tab of Studio" />

<Tabs>
  <TabItem label="Back Face">
    <img src="../assets/studio/general/View-Selector-Face.jpg" width="800" height="450" alt="Back face selected on View Selector widget in 3D viewport" />
  </TabItem>
  <TabItem label="Corner">
    <img src="../assets/studio/general/View-Selector-Corner.jpg" width="800" height="450" alt="Corner selected on View Selector widget in 3D viewport" />
  </TabItem>
</Tabs>

## Display options

### Grid and wireframe

A visual grid or wireframe view can be toggled through the buttons in the **Settings** section.

<img src="../assets/studio/general/View-Tab-Grid-Options.png" width="782" alt="Grid and wireframe tools indicated in View tab of Studio" />

<Tabs>
  <TabItem label="Default">
    <figure>
      <img src="../assets/studio/general/Grid-Options-Default.jpg" width="800" alt="Default 3D viewport with no grid or wireframe options enabled" />
    </figure>
  </TabItem>
  <TabItem label="Show grid">
    <figure>
      <img src="../assets/studio/general/Grid-Options-Show-Grid.jpg" width="800" height="450" alt="Show Grid toggled in View tab, revealing a 3D grid on the Y plane" />
      <figcaption>The **Show Grid** button toggles a 3D grid on the **Y** plane, as well as an axis indicator at (**0**,&nbsp;**0**,&nbsp;**0**). If showing, the radio buttons directly to the left of the button set the grid lines to be 2, 4, or 16 studs apart.</figcaption>
    </figure>
  </TabItem>
  <TabItem label="Grid material">
    <figure>
      <img src="../assets/studio/general/Grid-Options-Grid-Material.jpg" width="800" height="450" alt="Grid Material toggled in View tab, showing a flat grid material on all non-textured surfaces" />
      <figcaption>For 3D objects without an applied `Class.Texture`, the **Grid Material** button overlays a flat "grid&nbsp;material" on all surfaces.</figcaption>
    </figure>
  </TabItem>
  <TabItem label="Wireframe rendering">
    <figure>
      <img src="../assets/studio/general/Grid-Options-Wireframe-Rendering.jpg" width="800" height="450" alt="Wireframe Rendering toggled in View tab, changing the editor view to wireframe rendering mode" />
      <figcaption>The **Wireframe Rendering** button changes the editor view to wireframe rendering mode.</figcaption>
    </figure>
  </TabItem>
</Tabs>

### UI Visibility

Toggles the visibility of on-screen user interface elements in the 3D viewport.

<img src="../assets/studio/general/View-Tab-UI-Visibility.png" width="782" alt="UI Visibility toggle indicated in View tab of Studio" />

<Tabs>
  <TabItem label="On-screen UI visible">
    <img src="../assets/studio/general/Viewport-UI-Visibility-On.jpg" width="800" height="360" alt="UI Visibility toggled on (visible) for 3D viewport" />
  </TabItem>
  <TabItem label="On-screen UI hidden">
    <img src="../assets/studio/general/Viewport-UI-Visibility-Off.jpg" width="800" height="360" alt="UI Visibility toggled off (hidden) for 3D viewport" />
  </TabItem>
</Tabs>

### Selection style

To display **outlines** and/or **bounding boxes** around selected objects, choose an option from the **Selection Style** menu. You can also customize the thickness, color, and other aspects of outlines and bounding boxes through the **Studio&nbsp;Settings** menu.

<img src="../assets/studio/general/View-Tab-Selection-Style.png" width="670" alt="Selection Style menu indicated in View tab of Studio" />

<img src="../assets/studio/general/Selected-Object-Bounding-Box.jpg" width="800" alt="Selected part showing both its selection outline and a bounding box" />

<Alert severity="info">
While in a [collaborative session](../projects/collaboration.md) in Studio, bounding boxes only appear to you, not to others in the session.
</Alert>

## Stats

<img src="../assets/studio/general/View-Tab-Stats-Tools.png" width="670" alt="Diagnostic stats tools indicated in View tab of Studio" />

<table>
<thead>
  <tr>
    <th>Action</th>
    <th>Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>**Stats**</td>
    <td>Shows detailed experience stats.</td>
  </tr>
  <tr>
    <td>**Render**</td>
    <td>Shows detailed graphics and performance data.</td>
  </tr>
  <tr>
    <td>**Physics**</td>
    <td>Shows detailed physics data.</td>
  </tr>
  <tr>
    <td>**Network**</td>
    <td>Shows detailed network stats.</td>
  </tr>
  <tr>
    <td>**Summary**</td>
    <td>Shows a summary of stats data.</td>
  </tr>
  <tr>
    <td>**Clear**</td>
    <td>Removes all stats from the screen.</td>
  </tr>
</tbody>
</table>
