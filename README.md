### Mend Global Repo Configuration

This repository contains your Mend Global Repo Configuration.
It can be configured via the following configuration files: repo-config.json and global-config.json.

The [global-config.json](https://docs.mend.io/bundle/integrations/page/global_repo_configuration.html#GlobalRepoConfiguration-global-config.json) file lets you define global configurations for the integration.
<br/><br/>
The [repo-config.json](https://docs.mend.io/bundle/integrations/page/global_repo_configuration.html#GlobalRepoConfiguration-repo-config.json) file lets you apply configuration parameters for a Mend scan across all of your integrated repositories. All integrated repositories will inherit the configuration parameters set in this file, unless explicitly overridden by a local .mend (formerly .whitesource) file in the relevant repository.


**Note: This repository does not support changes to the configuration files done via pull requests. Doing so will result in unexpected/unknown strange behavior. Any edits must be committed directly to the default branch of the repository. Due to this, branch protection rules should not be applied to this repository.**


---

:question: Got questions? Check out the Global Repo Configuration [docs](https://docs.mend.io/bundle/integrations/page/global_repo_configuration.html).
If you need any further assistance then you can also [request help here](https://whitesourcesoftware.force.com/CustomerCommunity/s).