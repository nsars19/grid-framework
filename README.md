# grid-framework

Part of the Odin Project's [curriculum](https://www.theodinproject.com/courses/html-and-css/lessons/design-your-own-grid-based-framework). 

A scss framework built on a 12-cell grid.

How To Use Containers:

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

How To Use Columns:

Columns can be created with <code>.col</code>
To specify how many cells of the row to span any number from 1 through 12 can be used with <code>.col-*</code>
Breakpoints can also be added to columns. When the screen size reaches a breakpoint the column will change width to 100%.
Breakpoints can be used alone: <code>.col-xs</code>, <code>.col-sm</code>, <code>.col-md</code>, <code>.col-lg</code>, <code>.col-xl</code>,
or with a given grid-column width with <code>.col-md-\*</code>
