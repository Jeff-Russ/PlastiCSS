# PlastiCSS

## A small SASS library for creating responsive styles

#### Current State

PlastiCSS is still a baby. It was orginally a fork of Twitter Boostrap I decided to delete all of that and start over. 

#### Why?

I want raw materials (SASS mixins, functions, placeholders, etc) to generate CSS for pages which have no horizontal scrolling: fonts inside buttons and tiles are resized by viewport width, as are their containers so everything stays in ratio, but the width is not scaled at a 1:1 ratio with viewport. I'm using calc functions to scale margins and widths non-linearly to keep things legible and uncluttered but not too sparse. 
