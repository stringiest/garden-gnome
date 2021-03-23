# Garden Gnome
This website was conceived to help me to keep track of the plants in my garden, and the various maintenance tasks required for those plants.

## Background
I have an 80ft garden with mature planting, including a pond and a chicken run. Some of the planting is to my taste, some is not. The pond needs fairly major renovation. The garden has many shrubs which require regular maintenance, and I also want to grow vegetables. I don't yet have a handle on which plants are where. I have plans to replace some of the planting.

## Themes
There are four themes to the project:
1. A planning tool, to map out the existing garden & planting, and to plan for future changes.
2. A scheduling tool
    * to record regular maintenance needed for existing planting
    * to track watering of plants, particularly in the summer
    * to record annual seed sowing & planting out
3. A renovation plan, to record planned renovation works.
4. A wishlist, to record plants that I would like to add to the garden.

### Planning Notes
Sections 2-4 are fairly straightforward, and can be done using basic CRUD functionality. 

The plant database for section two could either contain plants added individually, with their pruning, feeding, habitat etc, or plant info could be pulled through from an external API.

### User stories
```
As a gardener, 
so that I can record my plants, 
I want to be able to draw a plan of my garden
```
```
As a gardener,
So that I can place plants appropriately,
I want to track the sunshine received by the garden.
```
```
As a gardener,
So that I don't plant competing plants,
I want to be able to add my existing plants to the plan.
```
```
As a gardener,
So that I can keep my garden tidy,
I want to be able to record when plants need recurring maintenance.
```
```
As a gardener,
So that I know which jobs to do next,
I want to be able to mark plant maintenance tasks as completed.
```
```
As a gardener,
So that I can grow vegetables,
I want to create a schedule reminding me to plant vegetable seeds.
```
```
As a gardener,
So that I don't kill my plants,
I want to record how often they need watering.
```
```
As a gardener,
So that I don't overwater my plants,
I want to record when they were last watered.
```
```
As a gardener,
So that I can preserve the lifespan of my sheds & fences,
I want to record recurring tasks for painting them.
```