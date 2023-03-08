# Identity Management

## GitHub Authentication

If your cluster domain has changed you will need to update the Oauth callback URL.

1. Go to: [NA-SSA Apps](https://github.com/organizations/redhat-openinfra-lab/settings/applications/), [OCP Oauth](https://github.com/organizations/redhat-openinfra-lab/settings/applications/2086423)
1. Update the `Authorization callback URL` '<https://oauth-openshift.apps.[cluster> name].[domain name]/oauth2callback/GitHub'
1. Click `Update Application`

## Links

- [Identity Provider Examples](https://github.com/kenmoini/openshift-identity-crisis)
