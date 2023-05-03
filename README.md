# Reveal.js plugin for github cards

Used github cards from https://github.com/lepture/github-cards with slight changes to make it work with reveal

# Install

Source the script:

	<script src="github-cards/github-cards.js"></script>

Add the event listener:

    Reveal.addEventListener('github-card', function(e) {
        github_cards(Reveal.getCurrentSlide(), document);
    });

# Use

Same as describe in https://github.com/lepture/github-cards:

	<div class="github-card" data-user="lepture" data-repo="github-cards"></div>
	
