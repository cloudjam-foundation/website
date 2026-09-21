<script lang="ts">
	let { class: className }: { class: string } = $props();
</script>

<svg
	id="logo"
	class={className}
	viewBox="0 0 1534 1534"
	fill="none"
	xmlns="http://www.w3.org/2000/svg"
>
	<path
		d="M774.227 1188.65L165.637 635.429L533.469 465.611L1351.15 793.793L774.227 1188.65Z"
		fill="#3A0770"
		stroke="black"
		stroke-width="69"
	/>
	<path
		d="M533.343 424.693L409.708 524.497L326.182 829.776L100.987 624.299L533.343 424.693Z"
		fill="#23073C"
		fill-opacity="0.91"
	/>
	<path
		d="M646.135 807.855L325.536 830.191L482.731 674.931L646.135 807.855Z"
		fill="#5F1D99"
		fill-opacity="0.61"
	/>
	<path
		d="M326.185 829.771L409.711 524.493L482.751 674.965L326.185 829.771Z"
		fill="#99949D"
		fill-opacity="0.59"
	/>
	<path
		d="M907.212 771.838L533.34 424.691L1006.18 613.823L907.212 771.838Z"
		fill="#8358A8"
		fill-opacity="0.92"
	/>
	<path
		d="M482.75 674.969L907.218 771.84L533.347 424.693L409.711 524.497L482.75 674.969Z"
		fill="#744B98"
		fill-opacity="0.52"
	/>
	<path
		d="M616.654 1095.75L497.107 818.255L646.761 807.401L616.654 1095.75Z"
		fill="#A795B8"
		fill-opacity="0.48"
	/>
	<path
		d="M616.654 1095.75L646.76 807.401L787.547 922.857L616.654 1095.75Z"
		fill="#A795B8"
		fill-opacity="0.17"
	/>
	<path
		d="M787.551 922.857L482.731 674.93L907.199 771.801L846.649 863.493L787.551 922.857Z"
		fill="#B997D0"
	/>
	<path
		d="M1428.9 784.102L907.198 771.804L1006.17 613.79L1428.9 784.102Z"
		fill="#744B98"
		fill-opacity="0.47"
	/>
	<path
		d="M846.646 863.494L1428.9 784.098L1169.07 887.388L1095.87 1012.19L846.646 863.494Z"
		fill="white"
		fill-opacity="0.97"
	/>
	<path d="M771.658 1233.92L846.649 863.494L910.359 1139.22L771.658 1233.92Z" fill="white" />
	<path
		d="M771.657 1233.93L615.152 1091.19L846.649 863.497L907.198 771.804L1428.21 784.222L771.657 1233.93Z"
		fill="#120117"
		fill-opacity="0.66"
	/>
</svg>

<style>
	#logo {
		cursor: pointer;
		scale: 1;
		transition: all ease 1s;
		animation: fly-in 3s ease forwards;
	}

	@keyframes fly-in {
		0% {
			opacity: 0.2;
			transform: translateX(10px);
			rotate: 12deg;
			scale: 0.5;
		}
		100% {
			opacity: 1;
			transform: translateX(0);
			rotate: -94deg;
			scale: 1;
		}
	}

	#logo path {
		transition: transform 0.45s cubic-bezier(0.2, 0.8, 0.2, 1);
		transform-box: fill-box;
		transform-origin: center;
	}

	#logo:hover path:nth-of-type(1) {
		transform: translate(-30px, -20px) scale(1.03);
	}
	#logo:hover path:nth-of-type(2) {
		transform: translate(-55px, -35px) scale(1.08);
	}
	#logo:hover path:nth-of-type(3) {
		transform: translate(-45px, 20px) scale(1.06) rotate(6deg);
	}
	#logo:hover path:nth-of-type(4) {
		transform: translate(-65px, 10px) scale(1.04);
	}
	#logo:hover path:nth-of-type(5) {
		transform: translate(25px, -45px) scale(1.07) rotate(-7deg);
	}
	#logo:hover path:nth-of-type(6) {
		transform: translate(-10px, -30px) scale(1.05);
	}
	#logo:hover path:nth-of-type(7) {
		transform: translate(-30px, 45px) scale(1.08) rotate(-6deg);
	}
	#logo:hover path:nth-of-type(8) {
		transform: translate(5px, 55px) scale(1.05) rotate(7deg);
	}
	#logo:hover path:nth-of-type(9) {
		transform: translate(25px, 10px) scale(1.07);
	}
	#logo:hover path:nth-of-type(10) {
		transform: translate(60px, -30px) scale(1.06);
	}
	#logo:hover path:nth-of-type(11) {
		transform: translate(65px, 20px) scale(1.08) rotate(6deg);
	}
	#logo:hover path:nth-of-type(12) {
		transform: translate(20px, 60px) scale(1.05);
	}
	#logo:hover path:nth-of-type(13) {
		transform: translate(45px, 50px) scale(1.08) rotate(7deg);
	}
</style>
