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
} 

mutation addFriend($friendId: ID!) {
  addFriend(friendId: $friendId) {
    _id
    username
    friendCount
    friends {
      _id
      username
    }
  }
}


mutation addReaction($thoughtId: ID!, $reactionBody: String!) {
  addReaction(thoughtId: $thoughtId, reactionBody: $reactionBody) {
    _id
    reactionCount
    reactions {
      _id
      reactionBody
      createdAt
      username
    }
  }
}

{
  "thoughtId": "6253112af46a080e6f90dc9a",
  "reactionBody": "I agree!"
}

mutation addThought($thoughtText: String!) {
  addThought(thoughtText: $thoughtText) {
    _id
    thoughtText
    createdAt
    username
    reactionCount
  }
}

{
  "thoughtText": "I think GraphQL is pretty cool."
}

{
  me {
    thoughts {
      _id
      thoughtText
    }
  }
}

mutation login($email: String!, $password: String!) {
  login(email: $email, password: $password) {
    token
    user {
      _id
    }
  }
}

{
        "_id": "62530b403468750d6c769047",
        "username": "greg",
        "email": "greg@test.com",
        "password": "greg12345"
      
}
-->