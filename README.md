# ImagePicker
CIS 3515 Assignment 3 created by Philip Lapinski

## What's it about:
This app gives the user the option to pick from a spinner a selection that will populate an imageView below.
The key to this project is to make a custom adapter, in my case *GalaxyAdapter*, which will control how the data flows.
Then, we implement that adapter into our main to create the final product.

## The Requirements:
1. Must implement custom adapter extending BaseAdapter :heavy_check_mark:
2. No Item selected when app launches - instructions instead. :x:
3. View are different for each spinner state( image + text on dropdown, only text on select) :heavy_check_mark:
4. Text is centerd on select :heavy_check_mark:
5. Activity displays selected image :heavy_check_mark:
