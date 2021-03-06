---
name: Unsuspend an app installation
example: octokit.apps.unsuspendInstallation({ installation_id })
route: DELETE /app/installations/{installation_id}/suspended
scope: apps
type: API method
---

# Unsuspend an app installation

**Note:** Suspending a GitHub App installation is currently in beta and subject to change. Before you can suspend a GitHub App, the app owner must enable suspending installations for the app by opting-in to the beta. For more information, see "[Suspending a GitHub App installation](https://developer.github.com/apps/managing-github-apps/suspending-a-github-app-installation/)."

Removes a GitHub App installation suspension.

To unsuspend a GitHub App, you must be an account owner or have admin permissions in the repository or organization where the app is installed and suspended.

You must use a [JWT](https://developer.github.com/apps/building-github-apps/authenticating-with-github-apps/#authenticating-as-a-github-app) to access this endpoint.

```js
octokit.apps.unsuspendInstallation({
  installation_id,
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
    <tr><td>installation_id</td><td>yes</td><td>

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/apps/#unsuspend-an-app-installation).
