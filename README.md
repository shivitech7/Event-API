**AN EVENT API**

**BUILT USING**
- Node.Js
- Express.Js
- MongoDB Atlas

This contains 4 API's:
- Speaker API
- moderator API
- Document API (For uploading any document file in any format)
- Event API

**APPROACH**
- Every profile image or any document uploaded in event page instantly uploaded to database and in return gets the file path.

- Similarly when a speaker and moderators are created, instantly stored in their respective collections and in return as 
  API response get's speake'r Id and moderato'r Id (for now the entire speaker and moderator data is sent as json res.).
  
- And for Reading material and resources, the entire data need to be first converted to markdown at frontend, so that at place 
  of every document upladed there would be the path of that file which we get in API response and other formats of data is also 
  stored in their respective formats such as quoted text, bold, italian, etc.
  
- And after filling all other fields publish the event page which calls the event API then all data and speaker's and moderator's
  Id's are stored in event collection at database which holds entire event data and Id's of refrenced collections of speaker and moderator.
  
