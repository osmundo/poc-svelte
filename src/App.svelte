<script>
	import Header from './components/Header.svelte';
	import Main from './components/Main.svelte';
	import Footer from './components/Footer.svelte';
	import { ARTICLES } from './api/articles'; 
</script>

<Header headerTitle="Projeto HTML | REACT | NEXT" imagePath="http://placekitten.com/800/300" />
<Main articles={ARTICLES} />
<Footer textFooter="Lá Ele Inc" />
