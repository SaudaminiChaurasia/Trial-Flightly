README - Flightly Trial LookML Project
LookML Overview
LookML is a data modeling language for describing dimensions, fields, aggregates and relationships based on SQL.

LookML is powerful because it:

Is all about reusability: Most data analysis requires the same work to be done over and over again. You extract
raw data, prepare it, deliver an analysis… and then are never able touse any of that work again. This is hugely
inefficient, since the next analysis often involves many of the same steps. With LookML, once you define a
dimension or a measure, you continue to build on it, rather than having to rewrite it again and again.
Empowers end users: The data model that data analysts and developers create in LookML condenses and
encapsulates the complexity of SQL, it and lets analysts get the knowledge about what their data means out of
their heads so others can use it. This enables non-technical users to do their jobs — building dashboards,
drilling to row-level detail, and accessing complex metrics — without having to worry about what’s behind the curtain.
Allows for data governance: By defining business metrics in LookML, you can ensure that Looker is always a
credible single source of truth.
The Looker application uses a model written in LookML to construct SQL queries against a particular database that
business analysts can Explore on. For an overview on the basics of LookML, see What is LookML?

Learn to Speak Looker
A LookML project is a collection of LookML files that describes a set of related views, models, and Explores.

A view (.view files) contains information about how to access or calculate information from each table (or
across multiple joined tables). Here you’ll typically define the view, its dimensions and measures, and its field sets.
A model (.model file) contains information about which tables to use and how they should be joined together.
Here you’ll typically define the model, its Explores, and its joins.
An Explore is the starting point for business users to query data, and it is the end result of the LookML you are
writing. To see the Explores in this project, select an Explore from the Explore menu.
Exploring Data
Ad-hoc data discovery is one of Looker’s most powerful and unique features. As you evaluate use cases for your
trial, consider what business areas you would like to explore. Open the Explore menu in the main navigation to see
the Explores you are building.

The Development Workflow
To support a multi-developer environment, Looker is integrated with Git for version control. Follow these directions
to set up Git for your project. To edit LookML, expand the Develop drop-down and toggle on Development Mode. In
Development Mode, changes you make to the LookML model exist only in your account until you commit the
changes and push them to your production model.

Additional Resources
To learn more about LookML and how to develop visit:

Looker User Guide
Looker Help Center
Looker University

Quick Help

Metadata
Select a line of LookML for syntax validation and code help.
Shift
+
?
for keyboard shortcuts
