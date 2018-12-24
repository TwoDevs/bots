# bots

## The comment model
    class Comment # A single comment on a Page. Associated with a user and Thread.
    class CommentTree # Data structure representing a thread of comments on a page.
    class User # A user on a Site. Typically has a username. 
    class Page # A page on a Site.
    class Site # A social media website.
  
## Bot API
  ### Writer
    WriteComment(Comment, Page) # Posts a comment to a Page.
  ### Reader
    ParseComments(Page) [CommentTree] # Reads all comments from a page and parses into a list of CommentTrees.
  
  ### For later.
    LinkCommentTrees(CommentTree, CommentTree)
    
