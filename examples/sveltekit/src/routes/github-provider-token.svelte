<script>
	export let user;
	export let allRepos;
</script>

<p>
	<a href="/">[Home]</a> |
	<a href="/profile">[withPageAuth]</a>
</p>

<div>Hello {user.email}</div>
<p>Data fetched with provider token:</p>
<pre>{JSON.stringify(allRepos, null, 2)}</pre>
<p>user:</p>
<pre>{JSON.stringify(user, null, 2)}</pre>
