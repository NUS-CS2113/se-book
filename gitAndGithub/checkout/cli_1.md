Use the `checkout <commit-identifier>` command to change the working directory to the state it was in at a specific past commit.

* `git checkout v1.0`: loads the state as at commit tagged `v1.0`
* `git checkout 0023cdd`: loads the state as at commit with the hash `0023cdd`
* `git checkout HEAD~2`: loads the state that is 2 commits behind the most recent commit

For now, you can ignore the warning about ‘detached HEAD’.

<include src="sourcetree_1.md#checkout-before-ignore" />
