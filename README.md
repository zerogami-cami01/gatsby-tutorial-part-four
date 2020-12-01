## gatsby-tutorial part-four

1.  **Reference site**: 

    [Gatsby tutorial site]

    (https://www.gatsbyjs.com/tutorial/part-three/)  2020/12/02 Access date

2.  **What you can learn?**:

    Creating Nested Layout Components

    - Using Gatsby plugin
    - Creating layoout components

3.  **How was it?**

    [gatsby-plugin-emotion] @emotion/react error

    `The code samples in the documentation include imports that reference @emotion/core instead of @emotion/react.`

    - I handled this issue by specifying the version 10.0.5:
      `npm install gatsby-plugin-emotion @emotion-core@^10.0.5`

    `https://github.com/gatsbyjs/gatsby/issues/28063` solved for me thanks.