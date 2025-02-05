# dev-todo-readme
1) Keep a streak going
2) Work on tnsv-blog-blob
3) basic blog
   - use TNSV for this
   - uploads the article-submission-content and the href for the images to Mongodb
   - review old book-worm-blog for reference
   - organize a do-work-flow so that way I can just write the vanilla-js-express changes by directly committing to github and then merging the changes imediatly to the up and running nginx-express-pm2 server
      - I basically need to add routes for an admin verification so that way the blog only has one person posting
      - and then i need to have a seperate route just for the blog, so basically a blog route and then sub routes like
         - add a posting
         - removing a post
         - editing a post
         - uploading an image
            - this is complicated and needs to be thought out considering I would prefer to store the images in the frontend since it would be cheaper 
6) LATER: streamline updation of local vercel-port
   - it would look something like thi
   - git fetch the most recent copy
   - make updates to the available projects to display
   - make sure that that project is hyperlinked
   - have that example application be promoted to production on vercel
