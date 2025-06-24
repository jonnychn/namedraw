Webinar Name Draw

A simple, interactive HTML/JS tool to conduct live name draws for webinars or events. Paste up to 300 participant names, toggle privacy, and hit Hit Go! to randomly pick a winner with visual highlights and sound effects.

⸻

Features
	•	Bulk name input: Paste up to 300 full names (one per line).
	•	Privacy toggle: Hide last names (first name + initial) for anonymity.
	•	Toggle input: Show or hide the name input area before the draw.
	•	Toggle instructions: Show or hide usage instructions on demand.
	•	Demo data: Prefill the grid with 200 example names for testing.
	•	Animated draw: Rapidly highlights random names with a beep, then ends with a celebratory three-note jingle.
	•	Responsive grid: Names display in a fluid grid layout.

⸻

Usage
	1.	Clone or download this repository.
	2.	Open webinar_draw_game.html in your browser.
	3.	(Optional) Click Demo to populate 200 sample names.
	4.	Paste or edit names in the textarea (one full name per line, max 300).
	5.	Use the Hide last names checkbox to anonymize entries.
	6.	Click Toggle Privacy to hide/show the input area before drawing.
	7.	(Optional) Click Toggle Instructions for a quick usage guide.
	8.	When ready, click Hit Go!. The grid will disappear, names will flash randomly, and the final selection plays a happy jingle.

⸻

Customization
	•	Sound effects: In the <script> section, modify or replace the playBeep() and playHappy() functions with your own audio logic.
	•	Max names: Change the .slice(0, 300) limit in renderGrid() to adjust allowed entries.
	•	Styling: Update styles in the <style> block (colors, grid size, fonts) to fit your branding.
	•	Button text: Edit the inner text of #startBtn, #demoBtn, etc., to suit your tone.

⸻

Deployment

Simply host webinar_draw_game.html on any static file server or GitHub Pages. No build step required.

# Example: publish via GitHub Pages
git add webinar_draw_game.html README.md
git commit -m "Add name-draw game and README"
git push origin main


⸻

License

This project is released under the MIT License. Feel free to use, modify, and share!
