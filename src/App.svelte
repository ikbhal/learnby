<script>
let examples = [
	{
		link: 'https://medium.com/@tanunprabhu95/to-do-list-application-using-kotlin-using-android-studio-546e74ac75aa',
		title: 'Kotlin Todo App',
	},
	{
		link: 'https://pusher.com/tutorials/live-blog-kotlin-push-notifications/',
		title: 'Kotlin Blog App',
	}
];

let repls = [{
	link: 'https://learnby.vercel.app/',
	title: 'Kotlin Replit',
}];


let tutorials = [
	{
		link: 'https://beginnersbook.com/2017/12/kotlin-tutorial/',
		title: 'Beginners Book Kotlin Tutorial'
	},
	{
		link: 'https://www.programiz.com/kotlin-programming',
		title: 'Programiz Kotlin Tutorial'
	},
	{
		link: 'https://www.w3schools.com/kotlin/index.php',
		title: 'W3schol Kotlin Tutorial'
	},
	{
		link: 'https://www.tutorialspoint.com/kotlin/index.htm',
		title: 'Tutorial Point Kotlin Tutorial'
	},
	{
		link: 'https://www.javatpoint.com/kotlin-tutorial',
		title: 'Java Point Kotlin Tutorial'
	},

];

let youtubeVideos = [
	{
		link:  'https://www.youtube.com/watch?v=F9UC9DY-vIU',
		title: 'Kotlin Course - Tutorial for Beginners',
	}
];

let links = [
	{
		link: 'https://kotlinlang.org/',
		title: 'Kotlin Lang'
	},
	{
		link: 'https://play.kotlinlang.org/',
		title: 'Kotlin Play'
	}, 
	{
		link: 'https://play.kotlinlang.org/koans/overview',
		title: 'Kotlin Koans',
	}, 
	{
		link: 'https://kotlinlang.org/community/', 
		title: 'Kotlin community',
	}
];
</script>

<main>
<h1>Kotlin tutorials</h1>


<h3>Kotli Examples</h3>
<ul>
	{#each examples as example}
	<li>
		<a href={example.link}>
			{example.title}
		</a>
	</li>
	{/each}
</ul>

<h3>Kotlin Repl</h3>
<ul>
	{#each repls as repl }
	<li>
		<a href={repl.link}>{repl.title}</a>
	</li>
	{/each}
</ul>

<h3>Kotlin Tutorial</h3>
<ul>
	{#each tutorials as tutorial}
		<li>
			<a href={tutorial.link}> {tutorial.title} </a>
		</li>
	{/each}
</ul>

<h3>Kotlin Youtube</h3>
<ul>
	{#each youtubeVideos as yt}
	<li> <a href={yt.link}>{yt.title}</a></li>
	{/each}
</ul>

<h3>Links</h3>
<ul>
	{#each links as link}
	<li> <a href={link.link}> {link.title} </a></li>
	{/each}
</ul>

</main>

<style>
main {
	margin: 50px;
}

ul {
	border: 1px solid grey;
	border-radius: 6px;
	padding: 10px;
}
ul li {
	list-style:  none;
}
</style>