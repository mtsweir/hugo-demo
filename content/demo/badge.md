---
title: "Badge"
date: 2022-03-28T22:20:27+13:00
draft: false
status: Stable
intro: Badges are for showing a product highlight. They're ideal for getting a user's attention.
---

<span class="pf-badge pf-badge-new" aria-label="New"></span>
<span class="pf-badge pf-badge-sale" aria-label="Sale"></span>
<span class="pf-badge pf-badge-fav pf-badge-icon" aria-label="Staff Pick">
	<svg class="pf-icon">
		<use xlink:href="#icon-heart"></use>
	</svg>
</span>
<span class="pf-badge pf-badge-promo pf-badge-secondary" aria-label="Promo"></span>

<script type="text/plain" class="language-markup">
<span class="pf-badge pf-badge-new" aria-label="New"></span>
<span class="pf-badge pf-badge-sale" aria-label="Sale"></span>
<span class="pf-badge pf-badge-fav pf-badge-icon" aria-label="Staff Pick">
	<svg class="pf-icon">
		<use xlink:href="#icon-heart"></use>
	</svg>
</span>
<span class="pf-badge pf-badge-promo pf-badge-secondary" aria-label="Promo"></span>
</script>

<section>
	<h2 class="h5">Table of definitions</h2>
	<p>The visual appearance is set using one of the following classes: <b>pf-badge-new</b>, <b>pf-badge-sale</b>, <b>pf-badge-fav</b>, or <b>pf-badge-promo</b></p>
	<div class="pf-table-responsive">
		<table class="docs-table">
			<thead>
				<tr>
					<th>Class</th>
					<th>Description</th>
				</tr>
			</thead>
			<tbody>
				<tr>
					<th>pf-badge</th>
					<td>The default internal sizing and structure of the badge. The default badge text colour is white.</td>
				</tr>
				<tr>
					<th>pf-badge-secondary</th>
					<td>Changes the default shape from circular to a pill-shape.</td>
				</tr>
				<tr>
					<th>aria-label</th>
					<td>The aria-label attribute by default provides a description for screenreaders, this attribute is also referenced in CSS to display use the same attribute as the badge label text.</td>
				</tr>
				<tr>
					<th>pf-badge-icon</th>
					<td>This is required when only displaying an icon, the visual text is hidden in CSS but remains accessible via the aria-label attribute.</td>
				</tr>
			</tbody>
		</table>
	</div>
</section>
