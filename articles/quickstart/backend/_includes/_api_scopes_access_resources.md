Scopes let you define which resources can be accessed by the user with a given Access Token. For example, you might choose to give the read access to the `messages` resource if a user has the manager access level, and a write access to that resource if they have the administrator access level. 

To configure scopes, in your Auth0 dashboard, in the [APIs](${manage_url}/#/apis) section, click the **Scopes** tab. Configure the scopes you need.

![Configure Scopes](/media/articles/server-apis/configure-scopes.png)

::: note
This example uses the `read:messages` scope.
:::
