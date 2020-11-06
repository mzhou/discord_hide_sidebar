Copy and paste the below code into a bookmark's location, then add that bookmark to your toolbar.

Click to hide/unhide the Discord sidebar.

```
javascript:void((() => {
	let channels = document.getElementsByClassName('sidebar-2K8pFh')[0];
	let servers = document.getElementsByClassName('guilds-1SWlCJ')[0];
	let servers_right = document.getElementsByClassName('base-3dtUhz')[0];
	let already_hidden = channels.style.display === 'none';
	if (already_hidden) {
		channels.style.display = '';
		servers.style.display = '';
		servers_right.style.left = '72px';
	} else {
		channels.style.display = 'none';
		servers.style.display = 'none';
		servers_right.style.left = '0';
	}
})());
```
