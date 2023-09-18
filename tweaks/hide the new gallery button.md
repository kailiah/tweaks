# Hide the '+ new' gallery button



<table border="0">
 <tr>
    <td><i>before tweak</i></td>
    <td><i>after tweak</i></td>
 </tr>
 <tr>
    <td><img alt="before tweak" src="https://i.imgur.com/qfll0sL.png"></td>
    <td><img alt="after tweak" src="https://i.imgur.com/WGIFyAO.png"></td>
 </tr>
</table>

## css

```css
/* ========== HIDE THE '+ NEW' GALLERY BUTTON ========== */
.notion-gallery-view
  .notion-selectable.notion-collection_view-block
  div
  + [role="button"],
.notion-gallery-view
  .notion-selectable.notion-collection_view_page-block
  div
  + [role="button"] {
  display: none !important;
}
```
