# grid-framework

Part of the Odin Project's [curriculum](https://www.theodinproject.com/courses/html-and-css/lessons/design-your-own-grid-based-framework). 

A scss framework built on a 12-cell grid.

<h4>How To Use Containers</h4>

To use the grid a <code>.container</code> element must be used. Each container spans 12 columns wide, with rows being created implicitly.
Containers can span the full width of the page, or be capped at a specific breakpoint by add the preferred size to <code>.container-*</code>.

Available Containers:
<table>
  <tr>
    <th>Class name</th>
    <th>Max Width</th>
  </tr>
  <tr>
    <td>
      <code>.container</code>
    </td>
    <td>
      100%
    </td>
  </tr>
  <tr>
    <td>
      <code>.container-sm</code>
    </td>
    <td>
      540px
    </td>  
  </tr>
   <tr>
    <td>
      <code>.container-md</code>
    </td>
    <td>
      720px
    </td>  
  </tr>
   <tr>
    <td>
      <code>.container-lg</code>
    </td>
    <td>
      960px
    </td>  
  </tr>
  <tr>
    <td>
      <code>.container-xl</code>
    </td>
    <td>
      1140px
    </td>  
  </tr>
</table>  

In order to place content inside of the grid columns must be nested within the <code>.container</code> element.
Columns default to 3 cells wide, but can be sized from 1 through 12 cells. Having more than 12 cells per row will implicitly create
new rows.

<h4>How To Use Columns</h4>

Columns can be created with <code>.col</code>
To specify how many cells of the row to span any number from 1 through 12 can be used with <code>.col-*</code>
Breakpoints can also be added to columns. When the screen size reaches a breakpoint the column will change width to 100%.
Breakpoints can be used alone: <code>.col-xs</code>, <code>.col-sm</code>, <code>.col-md</code>, <code>.col-lg</code>, <code>.col-xl</code>,
or with a given grid-column width with <code>.col-md-\*</code>, which will make a column * units wide until the breakpoint.


<h4>Several utility classes are also provided<h4>

To change the display of an element <code>.d-*</code> can be used with any display value

To change the position of an element <code>.p-*</code> can be used with any position value

To float an element <code>.float-left</code> or <code>.float-right</code>

To remove the default 20px gap <code>.no-gap</code>

To add a full border to elements <code>.border</code>

to add border by side use <code>.border-*</code> with either top, bottom, left, or right

To place items:
  <ul>
    <li>justify-content: <code>jc-*</code></li>
    <li>align-content: <code>ac-*</code></li>
    <li>justify-items: <code>ji-*</code></li>
    <li>align-items: <code>ai-*</code></li>
    <li>place-content: <code>pc-*</code></li>
    <li>place-items: <code>pi-*</code></li>
    <li>justify-self: <code>js-*</code></li>
    <li>align-self: <code>as-*</code></li>
    <li>place-self: <code>ps-*</code></li>
  </ul>

Each of the placement classes is used with their respective values
