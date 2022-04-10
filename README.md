# deep-thoughts

<!-- npm install react-router-dom@5 -->
<!-- queries
query {
  # query all thoughts
  thoughts {
    _id
    username
    thoughtText
    reactions {
      _id
      createdAt
      username
      reactionBody
    }
  },

  # query a single thought, use the `_id` value of a thought that returned from a previous query
  thought(_id: "<thought-id-here>") {
    _id
    username
    thoughtText
    createdAt
    reactions {
      username
      reactionBody
    }
  },

   # find a username from your previous query's results and paste it in for `<username-goes-here>` (i.e. "Wilton18")
  thoughts(username: "Liam.Hansen") {
    username
    thoughtText
  }
} -->