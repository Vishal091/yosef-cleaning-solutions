# Yosef Cleaning Solutions Website

A responsive single-page website concept for Yosef Cleaning Solutions, built with HTML, CSS, and JavaScript. The design uses forest green, sage, and warm cream with service cards, customer testimonials, mobile navigation, and a quote-request form.

## Preview locally

Open `index.html` in a browser, or run `python -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Before customer launch

The Vercel URL is a presentation preview, not a completed production handoff. The quote form is intentionally non-functional until a real email/form endpoint is configured, and the chatbot is a static FAQ assistant rather than generative AI.

## Before launch

- Confirm the relationship between Yosef, Jose, Luna Services, and Aida mentioned in the supplied customer reviews. The site labels reviewers generically and includes a transparency note.
- Verify the Philadelphia service area and the list of services.
- Add a real phone number and business email.
- Connect the quote form to a working email or form endpoint. The current form is intentionally a demo and does not transmit or store submissions.
- Review image licensing/availability and test on mobile.

## Deployment

The current customer preview is hosted on Vercel: https://yosef-cleaning-solutions.vercel.app/.

### Deploy to Vercel

This is a static HTML/CSS/JavaScript website. No build command or framework is required.

1. Sign in to [Vercel](https://vercel.com/) and choose **Add New → Project**.
2. Import `Vishal091/yosef-cleaning-solutions` from GitHub and authorize access if prompted.
3. In project settings, choose **Other** as the framework preset if Vercel does not detect a static site automatically.
4. Leave **Build Command** and **Output Directory** empty/default; the site files live in the repository root.
5. Click **Deploy**. Vercel will provide a `.vercel.app` URL.
6. Test the homepage, FAQ chatbot and mobile layout on the deployed URL.
7. For a custom domain, add it in **Project → Settings → Domains** and follow Vercel's DNS instructions.

The `vercel.json` file adds basic security headers and a short cache duration for the chatbot script. The quote form is still a demo and does not transmit submissions. The chatbot is a static FAQ assistant, not a generative AI service.
