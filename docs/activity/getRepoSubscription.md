---
name: Get a repository subscription
example: octokit.activity.getRepoSubscription({ owner, repo })
route: GET /repos/{owner}/{repo}/subscription
scope: activity
type: API method
---

# Get a repository subscription

```js
octokit.activity.getRepoSubscription({
  owner,
  repo,
});
```

## Parameters

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>required</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>owner</td><td>yes</td><td>

</td></tr>
<tr><td>repo</td><td>yes</td><td>

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/activity/watching/#get-a-repository-subscription).
