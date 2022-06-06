<script>
	import DONASI from '../components/DONASI.svelte';
	import Header from '../components/Header.svelte';
	import Welcome from '../components/Welcome.svelte';
	import Promo from '../components/Promo.svelte';
	import Footer from '../components/Footer.svelte';
	import {charities} from '../Data/charities.js';
	let title = "DONASI";
	
</script>
<Header />
<Welcome />
<DONASI {charities} />
<Footer   />