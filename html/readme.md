# ICPSR Notebooks


## Steps to run a mounted notebook in the ICPSR Data Commons

1. Login at [ somewhere TDB later ] using your username and password.

2. Navigate to the `Workspace` page, select the workspace named `A collection of Jupyter notebooks` (it will take several minutes to launch).
3. Navigate to the `icpsr-notebook` directory. Double click on the notebook you wish to run to open it. From the navigation bar on the top left, click "Run" and then select "Run All Cells" to execute the notebook. If you are running the notebook in our Workspace, you should not need to install dependencies.
4. If a notebook requires an API key, run [Gen3 Auth Helper](https://uc-cdis.github.io/gen3sdk-python/_build/html/auth.html) as follows:

```
# Import Gen3Auth
from gen3.auth import Gen3Auth
# Generate the Gen3Auth class pointed at the data commons the user is in
auth = Gen3Auth()
```


## Notebooks overview

### "twitter_solutions" notebook:

I hope we can find somebody to fill this in with useful instructions

### "twitter_tutorial" notebook:

perhaps we can also provide some usefule instructions here as well.
