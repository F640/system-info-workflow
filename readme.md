# GitHub Runner System Information

If you are ever wondering about GitHub Runner specification, this repo will provide you some helpful information about it. Unlike official docs at [regular runners reference](https://docs.github.com/en/actions/reference/runners/github-hosted-runners) and [ large and GPU runners reference](https://docs.github.com/en/enterprise-cloud@latest/actions/reference/runners/larger-runners) which limited to CPU cores, RAM and ephemeral storage, my workflow gives you these information depending on runners:

- CPU name
- Runner IP address
- System disk size
- Environment variables (some redacted)
- Network cards
- Hypervisor
- And some more

If you need to see the information you can take a look at actions then view my recent runs. If i have not run it in a while and you are in need of latest information feel free to fork it then run the workflow script on your own.

If you are having any issues running my script feel free to open an issue or if you have made some improvement to my workslow script feel free to open a PR.

Runner images ref: https://github.com/actions/runner-images
