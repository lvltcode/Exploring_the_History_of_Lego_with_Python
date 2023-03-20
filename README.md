# Exploring the History of Lego with Python (Pandas & Matplotlib)
In this project, we will analyze a fascinating dataset on every single Lego block that has ever been built!
## **1. Introduction**

Everyone loves Lego (unless you ever stepped on one). Did you know by the way that "Lego" was derived from the Danish phrase leg godt, which means "play well"? Unless you speak Danish, probably not.

In this project, we will analyze a fascinating dataset on every single Lego block that has ever been built!

![https://s3.amazonaws.com/assets.datacamp.com/production/project_10/datasets/lego-bricks.jpeg](https://s3.amazonaws.com/assets.datacamp.com/production/project_10/datasets/lego-bricks.jpeg)


## **2. Reading Data**

A comprehensive database of lego blocks is provided by [Rebrickable](https://rebrickable.com/downloads/). The data is available as csv files and the schema is shown below.

![https://s3.amazonaws.com/assets.datacamp.com/production/project_10/datasets/downloads_schema.png](https://s3.amazonaws.com/assets.datacamp.com/production/project_10/datasets/downloads_schema.png)

Let us start by reading in the colors data to get a sense of the diversity of Lego sets!


## **3. Exploring Colors**

Now that we have read the `colors` data, we can start exploring it! Let us start by understanding the number of colors available.


## **4. Transparent Colors in Lego Sets**

The `colors` data has a column named `is_trans` that indicates whether a color is transparent or not. It would be interesting to explore the distribution of transparent vs. non-transparent colors.

## **5. Explore Lego Sets**

Another interesting dataset available in this database is the `sets` data. It contains a comprehensive list of sets over the years and the number of parts that each of these sets contained.

![https://imgur.com/1k4PoXs.png](https://imgur.com/1k4PoXs.png)

Let us use this data to explore how the average number of parts in Lego sets has varied over the years.

## **6. Lego Themes Over Years**

Lego blocks ship under multiple [themes](https://shop.lego.com/en-US/Themes). Let us try to get a sense of how the number of themes shipped has varied over the years.

## **7. Wrapping It All Up!**

Lego blocks offer an unlimited amount of fun across ages. We explored some interesting trends around colors, parts, and themes. Before we wrap up, let's take a closer look at the `themes_by_year` DataFrame you created in the previous step.
