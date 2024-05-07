# How to do PR reviews:

Most importantly, we will need to truly understand why we are doing PR reviews so we can continue to look for the key points while reviewing the PR.

Pull Request (PR) reviews are must-have when making changes to enterprise-level applications. There are three main reasons: 

1. Acting a gatekeeper in case unexpected code changes in the space (production environment)
2. Having another set of eyes to review developer’s code for potential improvements or errors
3. Sharing knowledge

Base on the above, we can see a few areas that we should take care of when reviewing PRs:

1. Understand the reason for the code change
    - Code lives, reviewer must take into considerations for long-term outcome/impact
2. Impact of the code - is the changed code under control? Even though it is not much trouble to roll back changes nowadays, but the production impact could be significant in terms of the business operation
3. Check if testing is done, including unit tests and integration/functional tests
    - It is always recommended to write unit test. Although it is not a must-have in many places, but try doing them when:
        - ou found yourself go back to the same place for debugging again and again
        - The logic is critical that have significant impact, unit test can give sense of safety
4. Tell the developers when you like the way they handles the code
    - No one doesn’t like compliment
5. Quality of the code - does new code follow company code standard (or industry standard)? is the code easy to understand and maintain?  May check the followings
    - Less code is best code: changes should be concise as code don’t need to be complex, even may not need the changes (similar code can be reused)
    - Styles:
        - Code indention and spacing 
        - Syntax (standard + subjectively)

&nbsp;

---

&nbsp;

*Last modified on May 7, 2024*