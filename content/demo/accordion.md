---
title: "Accordion"
date: 2022-03-24T15:26:07+13:00
draft: false
status: Stable
intro: An accordion lets users show and hide sections of related content on a page.
---

## Default

Click the accordions below to expand/collapse the accordion content.

<div class="doc-example">
<div class="pf-accordion" role="group">
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-Benefits" aria-describedby="hint-Benefits">
		<label for="acd-Benefits">
			Benefits
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-Benefits">
			<ul>
				<li>Absorbs quickly and keeps skin hydrated, nourished and soft&nbsp;</li>
				<li>High in anti-oxidants, vitamins A,B,C,E, Omega 3,6,7 and 9</li>
			</ul>
		</div>
	</div>
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-KeyIng" aria-describedby="hint-KeyIngredients">
		<label for="acd-KeyIng">
			Key Ingredients
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-KeyIngredients">
			<p>Cold pressed virgin coconut oil, macadamia, dilo and sikeci oil. Passionflower extracts and fresh coconut milk.</p>
		</div>
	</div>
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-Howto" aria-describedby="hint-HowToUse">
		<label for="acd-Howto">
			How to Use
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-HowToUse">
			<ul>
				<li>As a body moisturiser or for extra dry areas.</li>
				<li>Also an excellent cream to help prevent stretch marks during pregnancy.</li>
			</ul>
			<p><b>Handy Tip:</b> Apply to feet and hands at night and cover with socks/gloves. Wake up wonderfully soft and hydrated! Use as a styling aid for thick coarse hair.</p>
			<p><b>Professional Use:</b> Manicures, Pedicures, Body Wraps, Massage</p>
		</div>
	</div>
</div>
</div>

<script type="text/plain" class="language-markup">
<div class="pf-accordion" role="group">
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-Benefits" aria-describedby="hint-Benefits">
		<label for="acd-Benefits">
			Benefits
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-Benefits">
			<ul>
				<li>Absorbs quickly and keeps skin hydrated, nourished and soft&nbsp;</li>
				<li>High in anti-oxidants, vitamins A,B,C,E, Omega 3,6,7 and 9</li>
			</ul>
		</div>
	</div>
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-KeyIng" aria-describedby="hint-KeyIngredients">
		<label for="acd-KeyIng">
			Key Ingredients
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-KeyIngredients">
			<p>Cold pressed virgin coconut oil, macadamia, dilo and sikeci oil. Passionflower extracts and fresh coconut milk.</p>
		</div>
	</div>
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-Howto" aria-describedby="hint-HowToUse">
		<label for="acd-Howto">
			How to Use
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-HowToUse">
			<ul>
				<li>As a body moisturiser or for extra dry areas.</li>
				<li>Also an excellent cream to help prevent stretch marks during pregnancy.</li>
			</ul>
			<p><b>Handy Tip:</b> Apply to feet and hands at night and cover with socks/gloves. Wake up wonderfully soft and hydrated! Use as a styling aid for thick coarse hair.</p>
			<p><b>Professional Use:</b> Manicures, Pedicures, Body Wraps, Massage</p>
		</div>
	</div>
</div>
</script>

## Always open

Add the <code>checked</code> state to any input element to set the accordion item to be opened by default.

<div class="doc-example">
<div class="pf-accordion" role="group">
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-Benefits" aria-describedby="hint-Benefits" checked>
		<label for="acd-Benefits">
			Benefits
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-Benefits">
			<ul>
				<li>Absorbs quickly and keeps skin hydrated, nourished and soft&nbsp;</li>
				<li>High in anti-oxidants, vitamins A,B,C,E, Omega 3,6,7 and 9</li>
			</ul>
		</div>
	</div>
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-KeyIng" aria-describedby="hint-KeyIngredients">
		<label for="acd-KeyIng">
			Key Ingredients
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-KeyIngredients">
			<p>Cold pressed virgin coconut oil, macadamia, dilo and sikeci oil. Passionflower extracts and fresh coconut milk.</p>
		</div>
	</div>
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-Howto" aria-describedby="hint-HowToUse">
		<label for="acd-Howto">
			How to Use
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-HowToUse">
			<ul>
				<li>As a body moisturiser or for extra dry areas.</li>
				<li>Also an excellent cream to help prevent stretch marks during pregnancy.</li>
			</ul>
			<p><b>Handy Tip:</b> Apply to feet and hands at night and cover with socks/gloves. Wake up wonderfully soft and hydrated! Use as a styling aid for thick coarse hair.</p>
			<p><b>Professional Use:</b> Manicures, Pedicures, Body Wraps, Massage</p>
		</div>
	</div>
</div>
</div>

<script type="text/plain" class="language-markup">
<div class="pf-accordion" role="group">
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-Benefits" aria-describedby="hint-Benefits" checked>
		<label for="acd-Benefits">
			Benefits
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-Benefits">
			<ul>
				<li>Absorbs quickly and keeps skin hydrated, nourished and soft&nbsp;</li>
				<li>High in anti-oxidants, vitamins A,B,C,E, Omega 3,6,7 and 9</li>
			</ul>
		</div>
	</div>
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-KeyIng" aria-describedby="hint-KeyIngredients">
		<label for="acd-KeyIng">
			Key Ingredients
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-KeyIngredients">
			<p>Cold pressed virgin coconut oil, macadamia, dilo and sikeci oil. Passionflower extracts and fresh coconut milk.</p>
		</div>
	</div>
	<div class="pf-accordion-item">
		<input type="checkbox" id="acd-Howto" aria-describedby="hint-HowToUse">
		<label for="acd-Howto">
			How to Use
			<span class="pf-accordion-icon" aria-hidden="true"></span>
		</label>
		<div class="pf-accordion-content" id="hint-HowToUse">
			<ul>
				<li>As a body moisturiser or for extra dry areas.</li>
				<li>Also an excellent cream to help prevent stretch marks during pregnancy.</li>
			</ul>
			<p><b>Handy Tip:</b> Apply to feet and hands at night and cover with socks/gloves. Wake up wonderfully soft and hydrated! Use as a styling aid for thick coarse hair.</p>
			<p><b>Professional Use:</b> Manicures, Pedicures, Body Wraps, Massage</p>
		</div>
	</div>
</div>
</script>
