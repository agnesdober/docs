# Use: track your food!

You probably found Grocy looking for a way to keep inventory of your groceries - and as you guessed from the name, this is its main function. The following tutorial shows you *one* way of doing this. The nice thing about Grocy is that it's flexible, and you can adjust your setup and use according to what is important to you, so use this tutorial as a general guide to understanding how the seperate parts come together before setting up your own use.

## Goals

We will first set up the basic elements of working with Grocy: locations, quantity units, and product groups. This will help us then set up our products.

## Before you start

You should have a working grocy server or an installed windows app, with users configured.

## Manage Master Data

### The basic building blocks

You can find all of these elements under Manage master data in the side menu. These can always be edited later, including adding, modifying or deleting entries, so there is no need to worry if you leave something out. It's advisable to try and create these first before your products, as it will save you time from having to go back and edit either products or these categories.

**Locations.** You can add elements by clicking the add button on top, giving it a name, optionally a description, and selecting if it is a freezer or not. This latter checkbox is important if you will be using the thawing element later, allowing you to automatically set a short expiration date on items moved from a freezer to a non-freezer location. If you want to later edit a location, simply click on the edit button to take you back to these options. As a first step, try to add most of the locations you will be tracking.  

**Product groups.** Product groups allow you to later group certain types of products together, such as "Fruits and veggies" or "Spices" etc. Once you've added products, you will be able to filter them according to these. Go ahead and add as many product groups as you think you will need.

**Quantity units.** These units will appear with your products (e.g. a bottle of wine, a pack of pasta). Important to note as you configure these is that you are able to set later purchase quantities that differ from stock quantities. An example might be a toilet paper: you might by 1 pack that contains 16 rolls, so feel free to add as many units as you feel fit by clicking on the add button on top. This tutorial doesn't recommend starting out with precise measurements (these can be added later); focus first on getting to know how Grocy works and deciding on what aspect you wish to track. Is it important to know the precise amount to a gramm - and will you be tracking it every time you cook and consume? Or is it more important to track best before dates and stocked amounts? Use this tutorial to experiment and explore how you want to use Grocy.

**Products.** The entries here are the general descriptions of the types of products you will have (e.g. white flour, skim milk, white bread). The purchase action will use these entities to create your stock entries. You can create a new product by clicking the Add button on top. There are many options here, but this tutorial will only touch on some for the sake of getting started easily. All entries are later modifiable, if you decide on a method that better fits your needs.
1. Enter the name of the product and ignore the parent product field. 
   You can add a description if you'd like. If you have barcodes configured and plan to use this functionality, go ahead and add those as well.
2. The next required field is locations, which you can choose from the list - these are the entries we've set up in the Locations menu before.
3. If the product is something you feel you should always have in stock, use the minimum stock amount to select the appropriate number. These items will show up highlighted on the top of your stock overview if they fall below the selected amount. Ignore the accumulated checkbox.
4. Likewise, you may set default best before days for a product (e.g. seven days for a particular type of fruit) and default day best before days after you marked a product as opened. Products that have passed this date will show up in highlighted in your stock overview.
5. Product group is not a required field, but will help you sort and we've set it up before. Go ahead and select the appropriate one from the list.
6. Quantity unit purchase and stock are required fields. If these two match (you buy a bottle of milk and you want to track it in bottles), select the same for both. If they do not (a pack of toilet paper has 16 rolls or pieces), you can set the difference in the Factor purchase to stock quantity unit field. This will multiply the purchase (1) by the set amount (16) when you purchase, creating the appropriate stock number.
7. Check allow partial units in stock if needed. This will switch the input from whole numbers to decimals.
8.


## Purchase


## Stock overview



## Transfer



## Consume



## Inventory



## Shopping list


