## gatsby-tutorial part-four

1.  **Reference site**: 

    [Gatsby tutorial site]

    (https://www.gatsbyjs.com/tutorial/part-four/)  2020/12/03 Access date

2.  **What you can learn?**:

    Data in Gatsby

    - Recap of the first half of the tutorial
    - Data in Gatsby
    - How Gatsby uses GraphQL
    - Your first GraphQL query

3.  **How was it?**

    [gatsby-plugin-emotion] @emotion/react error

    `The code samples in the documentation include imports that reference @emotion/core instead of @emotion/react.`

    - I handled this issue by specifying the version 10.0.5:
      `npm install gatsby-plugin-emotion @emotion-core@^10.0.5`

    `https://github.com/gatsbyjs/gatsby/issues/28063` solved for me thanks.