# Reviewing proposed changes in a pull request
In a pull request, you can review and discuss commits, changed files, and the differences (or "diff") between the files in the base and compare branches.

## About reviewing pull requests
You can review changes in a pull request one file at a time. While reviewing the files in a pull request, you can leave individual comments on specific changes. After you finish reviewing each file, you can mark the file as viewed. This collapses the file, helping you identify the files you still need to review. A progress bar in the pull request header shows the number of files you've viewed. After reviewing as many files as you want, you can approve the pull request or request additional changes by submitting your review with a summary comment.

## Starting a review
1. Under your repository name, click  Pull requests.
![](https://docs.github.com/assets/images/help/repository/repo-tabs-pull-requests.png)

2. In the list of pull requests, click the pull request you'd like to review.

3. On the pull request, click  Files changed.
![](https://docs.github.com/assets/images/help/pull_requests/pull-request-tabs-changed-files.png)

4. Hover over the line of code where you'd like to add a comment, and click the blue comment icon. To add a comment on multiple lines, click and drag to select the range of lines, then click the blue comment icon.
![](https://docs.github.com/assets/images/help/commits/hover-comment-icon.gif)

5. In the comment field, type your comment.
![](https://docs.github.com/assets/images/help/pull_requests/comment-field.png)

6. Optionally, to suggest a specific change to the line or lines, click , then edit the text within the suggestion block.
![](https://docs.github.com/assets/images/help/pull_requests/suggestion-block.png)

7. When you're done, click Start a review. If you have already started a review, you can click Add review comment.
![](https://docs.github.com/assets/images/help/pull_requests/start-a-review-button.png)

Before you submit your review, your line comments are pending and only visible to you. You can edit pending comments anytime before you submit your review. To cancel a pending review, including all of its pending comments, scroll down to the end of the timeline on the Conversation tab, then click Cancel review.

![](https://docs.github.com/assets/images/help/pull_requests/cancel-review-button.png)

## Reviewing dependency changes
If the pull request contains changes to dependencies you can use the dependency review for a manifest or lock file to see what has changed and check whether the changes introduce security vulnerabilities. For more information, see "Reviewing dependency changes in a pull request."

1. On the pull request, click  Files changed.
![](https://docs.github.com/assets/images/help/pull_requests/pull-request-tabs-changed-files.png)

2. On the right of the header for a manifest or lock file, display the dependency review by clicking the  rich diff button.
![](https://docs.github.com/assets/images/help/pull_requests/dependency-review-rich-diff.png)

3.You may also want to review the source diff, because there could be changes to the manifest or lock file that don't change dependencies, or there could be dependencies that GitHub can't parse and which, as a result, don't appear in the dependency review.

To return to the source diff view, click the  button.
![](https://docs.github.com/assets/images/help/pull_requests/dependency-review-source-diff.png)

## Marking a file as viewed
After you finish reviewing a file, you can mark the file as viewed, and the file will collapse. If the file changes after you view the file, it will be unmarked as viewed.

1. On the pull request, click  Files changed.
![](https://docs.github.com/assets/images/help/pull_requests/pull-request-tabs-changed-files.png)

2. On the right of the header of the file you've finished reviewing, select Viewed.
![](https://docs.github.com/assets/images/help/pull_requests/viewed-checkbox.png)

## Submitting your review

After you've finished reviewing all the files you want in the pull request, submit your review.

1. On the pull request, click  Files changed.
![](https://docs.github.com/assets/images/help/pull_requests/pull-request-tabs-changed-files.png)

2. Above the changed code, click Review changes.
![](https://docs.github.com/assets/images/help/pull_requests/review-changes-button.png)

3. Type a comment summarizing your feedback on the proposed changes.
![](https://docs.github.com/assets/images/help/pull_requests/review-summary-comment-window.png)

4. Select the type of review you'd like to leave:
![](https://docs.github.com/assets/images/help/pull_requests/pull-request-review-statuses.png)

Select Comment to leave general feedback without explicitly approving the changes or requesting additional changes.
Select Approve to submit your feedback and approve merging the changes proposed in the pull request.
Select Request changes to submit feedback that must be addressed before the pull request can be merged.

5. Click Submit review.
