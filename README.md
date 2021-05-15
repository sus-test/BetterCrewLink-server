doctype html
head
	title BetterCrewLink Server
	link(rel="icon", href="https://github.com/OhMyGuus/BetterCrewLink/raw/nightly/src/renderer/logos/BCL-AppIcon.png", type="image/x-icon")
	meta(property='og:title' content='BetterCrewLink Server')
	meta(property='og:description' content='Voice server for Among Us proximity voice chat mod called BetterCrewLink')
	meta(property='og:image' content='https://github.com/OhMyGuus/BetterCrewLink/raw/nightly/src/renderer/logos/BCL-AppIcon.png')
	link(rel='stylesheet', href='/public/styles.css')


img(src="https://github.com/OhMyGuus/BetterCrewLink/raw/nightly/src/renderer/logos/sizes/256-BCL-Logo-shadow.png")
h1 BetterCrewLink Server
#crewinfo

	p This is a BetterCrewLink Server running on:
	br
	b #{address}
	p There #{connectionCount === 1 ? 'is' : 'are'} currently #{connectionCount} connected user#{connectionCount === 1 ? '' : 's'} 
	<hr>
	p
		a(href="https://github.com/OhMyGuus/BetterCrewLink/releases/latest", target="_blank")
			| To download BetterCrewLink
			| <b>Click here</b>
	<hr>
	 
		
#background-container
	#stars
	#stars2
	#stars3
