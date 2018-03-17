simple adaptive grid of 12 collumns
usage: create elem with class "row", in this element create elements with a class with this syntax:
col-<number> for very small screens
col-sm-<number> for small screens
col-md-<number> for medium screens
col-xl-<number> for extra large screens

where <number> is number of used collumns

for example:
<div class="row">
  <div class="col-12 col-md-6">elem</div>
</div>

inner element will occupy the entire width of the screen on extra small screens
and half the screen on medium and wider screens
