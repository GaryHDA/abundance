### Abundance

#### About this repo

This repo is part of the 2020-2021 beach litter surveillance project and part of the hammerdirt! infrastructure. Access is  public.

### Intended use

This repo is for the analysis of the abundance of anthropogenic litter identified along Swiss rivers and lakes. Completed analysis projects are displayed on the hammerdirt! app and the appropriate client app. Analysis is focussed on the quantities of objects found at different locations and will include (but not limited to):

1. Identifying the most common objects found at each location
2. Identifying the most common objects by material and use
3. Comparing quantities from different locations and different bodies of water 
4. Providing data models for the hammerdirt! client app.
5. Providing charts and graphs for articles

### Data access

Access to data is provided through the Jupyter notebook templates.

### Contributing

Follow these steps if you would like to submit a completed analysis or visualisation and have it included in a publication or on a client app:

1. Clone the repo
2. Start a branch titled <yourname_abundance>
3. In the notebook make sure to change the "save_prefix" value
4. Complete your analysis 
5. On your local generate .html output of the notebook
6. Send the .html doc to roger@hammerdirt.ch

If your analysis makes sense and provides an innovative or original view of the subject we will request the following:

1. A summary of your analysis
2. References/bibliography 
3. Full contact information 

__tips:__ Stay on topic. Follow the template model. There are/will be a couple examples to follow in the repo. If you follow that and your analysis makes sense it will be easy for us to generate the document for the application.

__What happens next?__: Your analysis will be visible by others interested in the topic, if our clients choose your analysis then it will be included in any publications ane you will be credited in the publication.

### The hammerdirt infrastructure:

These are the main components of the hammerdirt! infrastructure:

1. Data storage and distribution through the API:
  * api url: [https://mwshovel.pythonanywhere.com/](https://mwshovel.pythonanywhere.com/)
  * repo: [https://github.com/hammerdirt/hammerdirt_api](https://github.com/hammerdirt/hammerdirt_api)
  * Authenticated members can enter survey data and edit articles
  * Provides endpoints for client apps
  * Powered by Django REST
2. Data entry and management:
  * url: [https://www.hammerdirt.ch/](https://www.hammerdirt.ch/)
  * repo: [https://github.com/hammerdirt/pwa](https://github.com/hammerdirt/pwa)
  * Has access to POST and PUT endpoints
  * Includes WYISWYG editor by TinyMCE
  * Forms for entering survey data and commenting on articles
  * Built with ReactJS
3. Data visualisation, communication:
  * url: [https://www.plagespropres.ch/](https://www.plagespropres.ch/)
  * repo: [https://github.com/hammerdirt/client_pwa](https://github.com/hammerdirt/client_pwa)
  * Has access to GET endpoints
  * Built with ReactJS
4. Version control and collaboration:
  * version control : Git
  * collaboration: GitHub
  * url:[https://github.com/hammerdirt](https://github.com/hammerdirt) 


### About hammerdirt!

Hammerdirt! is a non-profit organisation based in Switzerland and dedicated to the collection, analysis and distribution of environmental data.

### Joining hammerdirt!

1. see hammerdirt.ch in the docs tab "members"
