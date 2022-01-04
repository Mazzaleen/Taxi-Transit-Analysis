# TaxiTransitAnalysis
New York taxi and transport analysis investigating how taxi fares vary by time and weather conditions. 

There was a bit of 'location matching' involved in this project, and it made our life very easy
   that the positions of the walls vs floors were represented as a list of lists when it came to
   quite a few aspects. Here are some examples:
    It made it easy
 to ensure the key-pressed code functioned properly, as we could easily check to see if the
 person was going to walk into a wall, and if that was the case to make sure that their position 
 did not change. It also allowed us to easily check that our player doesnt lose stamina if they
   hit a wall. This is because: by having this info stored as a list of lists, we could create a
   perfect mapping between the entries in this list of  lists, and the different coordinates in
   the game, hence making the 'location matching' very simple (especially with the built-in 'get'
   function. Every element in some list has a
   number attached to it, making it easy to match with the position of the person. And by having a
   list of list of elements (rather than just list of elements), we can also assign a number to
   each list, hence making all of our entries unique. 
   Tables are not designed with this idea in mind of giving every unique entry some number 
   corresponding to it (it might be for the rows but definitely not for columns). Another
   example is that we would make items disappear by dropping them from a list. This
   definitely would have been harder in a table, where it is not as easy to get rid 
   of one specific element (we are used to getting rid of entire rows or columns) 

   In comparison though, a table would have been handy for the background data. This data is 
   static and will not change, and so we do not necessarily need the accesibilty of lists
   for it. It also would have been significantly easier to read to visualize
