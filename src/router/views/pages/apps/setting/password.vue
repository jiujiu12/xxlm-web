<template>
	<Layout>
		<PageHeader :title="title"  />
	</Layout>
</template>

<script>
	import Layout from '@layouts/main'
	import PageHeader from '@components/page-header'

	/**
	 * Starter component
	 */
	export default {

		components: { Layout, PageHeader },
		data() {
			return {
				title: '修改密码',
			}
		},
	}
</script>


