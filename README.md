Stat 850 Project Description
================
Constanza Paz Avello Lefno, Yutong Liu, Lin Zhao

## Instructions

Each member of your team should modify this document in some way and
push their modifications to the repository in a separate commit. This
will ensure that you have set your repository up in a way that ensures
all group members are working with the same repository.

Note that you must compile your readme (this document) for it to
properly display as part of your github repository.

Once you have received feedback on your project proposal (via Canvas)
you may alter this README so that it describes your final project
instead of the project proposal.

## Data Set

Provide a link to your dataset here, and a description of the variables
in the data
set.

[FoodData](https://fdc.nal.usda.gov/fdc-datasets/FoodData_Central_csv_2020-04-29.zip)
is an integrated database that provides food component and nutrient
information.

Three tables from the database are chosen for this project:

  - food\_component.csv
  - food\_nutrient.csv
  - nutrient.csv

By combining three datasets together and selecting several variables, a
new dataset called **food\_dataset** is generated for further analysis.

Description of variables:

  - component\_name - *The kind of component, e.g. bone*

  - pct\_weight - *The weight of the component as a percentage of the
    total weight of the food*

  - is\_refuse - *Whether the component is refuse, i.e. not edible*

  - gram\_weight - *The weight of the component in grams*

  - nutrient\_amount - *Amount of the nutrient per 100g of food.
    Specified in unit defined in the nutrient table.*

  - min - *The minimum amount*

  - max - *The maximum amount*

  - median - *The median amount*

  - nutrient\_name - *Name of the nutrient*

  - nutrient\_unit - *The standard unit of measure for the nutrient (per
    100g of food)*

## Potential Topics to Explore Using the Data Set

Describe avenues you might explore using the data

There are several tables in the original database, we only take three of
them and merge the variables together by **fdc\_id**, which is a unique
permanent identifier of a food across tables. We would like to discover
potential recycling of non-edible food component which has relatively
higher nutrient.

1.  Explore the number of food components that are refuse or not and
    look for which food components are refuse.

2.  We could compare the pct\_weight and weight among food components
    that are refused and look for the higher pct\_weight and weight
    components, which are more potential recycling.

3.  Adjusted the nutrient amount with the same unit, such as mg.

4.  Explore the amount of each nutrient grouped by food component,
    focusing on the food components that are defined as refuse.

5.  If we find some nutrients with extreme content, we could look at the
    minimum, maximum, and median amount of these nutrients.

6.  Calculate the exact amount of each nutrient for each food component.

7.  Explore the higher amount of specific nutrients in the food
    component. Looking for which food component is suitable for an
    exacting specific nutrient, such as DHA.

Overall, we want to look for a higher amount of food components that are
refuse with a higher amount of beneficial nutrients.

We would like to find these potential recycling of non-edible food
components by exploring the total amount of components or the amount of
specific nutrients in the food component.

## Group Members

  - Constanza Paz Avello Lefno
  - Yutong Liu
  - Lin Zhao

## Reference

U.S. Department of Agriculture, Agricultural Research Service. FoodData
Central, 2019. fdc.nal.usda.gov.
