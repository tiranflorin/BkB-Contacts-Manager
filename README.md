# BackBone-Contacts-Manager

A Backbone.js working tutorial based on these tutsplus series: 
http://code.tutsplus.com/series/getting-to-know-backbonejs--net-24408

Additional features:

  * **Backend API integration for saving the contacts.**
    
Works based on a standard backend API:

  * GET /contacts/ ..... collection.fetch();
  * POST /contacts/ ... collection.create();
  * GET /contacts/1 ... model.fetch();
  * PUT /contacts/1 ... model.save();
  * DEL /contacts/1 ... model.destroy();
