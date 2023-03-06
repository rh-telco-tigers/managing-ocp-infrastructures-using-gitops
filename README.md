This multi-part blog series will cover how to deploy bare-metal server resources into an OCP cluster using Gitops tooling

In the first part of this series, I showed you how the to install the Assisted Service/CIM (Central Infrastructure Management) and how a cluster can be deployed in a declarative manner using approximately 9 YAML files.

https://www.myopenshiftblog.com/managing-ocp-infrastructures-using-gitops-part-1/
https://github.com/kcalliga/gitops-blog

In the second part of this series, we could see how that YAML files could be condensed into a single SiteConfig file.  The directory structure of the ztp-site-generator container was used to create the following GitHub repository.

https://www.myopenshiftblog.com/managing-ocp-infrastructures-using-gitops-part-2/
https://github.com/kcalliga/ztp-example/tree/main/argocd

In the third part, I will show how the SiteConfig can be parsed as part of a ZTP pipeline using Openshift Gitops.  These features can also be used to have objects (such as clusters) be automatically modified based on updates being made to the source GitHub repo.

https://www.myopenshiftblog.com/managing-ocp-infrastructures-using-gitops-part-3/
https://github.com/kcalliga/ztp-example/tree/v4.11.3-9
