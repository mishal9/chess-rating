# Chess coaching rating page

Static page for a blinded human-rating study of chess coaching. Raters open a personal link
(`#t=<token>`) sent by the study organiser; scores save to the study database.

The Supabase key in `index.html` is a publishable key, public by design. The database only
accepts saves for tokens issued by the organiser.
