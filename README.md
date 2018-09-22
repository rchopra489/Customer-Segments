# Customer Segments


# Project Context
Our client is an online retailer based in the UK. They sell all-occasion gifts, and many of their customers are wholesalers.

Most of their customers are from the UK, but they have a small percent of customers from other countries.
They want to create groups of these international customers based on their previous purchase patterns.
Their goal is to provide more tailored services and improve the way they market to these international customers.

# Current Solution
Currently, the retailer simply groups their international customers by country. As you'll see in the project, this is quite inefficient because:

There's a large number of countries (which kinda defeats the purpose of creating groups).
Some countries have very few customers.
This approach treats large and small customers the same, regardless of their purchase patterns.

# Our Role
The retailer has hired us to help them create customer clusters, a.k.a "customer segments," through a data-driven approach.

They've provided us a dataset of past purchase data at the transaction level (you'll see why this will be important).
Our task is to build a clustering model using that dataset.
Our clustering model should factor in both aggregate sales patterns and specific items purchased.

# Problem Specifics
It's always helpful to explicitly lay out the problem specifics before starting.

Deliverable: Clusters for customers

Machine learning task: Clustering

Target variable: N/A (Unsupervised learning)

Win condition: N/A (Subjective results)

Now that you have the context and problem specifics, let's dive right in!
