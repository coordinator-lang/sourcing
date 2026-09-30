# Nordicta Sourcing

Intern sökmotor för boende åt Nordicta Corporate Housing. Sidan är bara skalet: utan inloggning går ingenting att se eller söka.

- Inloggning: teamkontot i Supabase Auth.
- Data (förfrågningar, sökresultat, logg, bockar) ligger i Supabase med radnivåskydd – inte i det här repot.
- AI-sökningen körs i Supabase Edge Function `sourcing`. AI-nyckeln finns bara som hemlighet på servern.

Sidan byggs från projektmappen (`build/build-app.js` → `app/web/index.html`). Redigera inte `index.html` här direkt.
