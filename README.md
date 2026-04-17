# Yashar Heidari — 17 Industry-Tailored Portfolios

Live site: `https://yheidari.github.io/`

One candidate. Seventeen portfolios. Each tailored to the exact role and industry of the matching CV, and aligned to every requirement in the CV master reference guide:

- Target job title surfaced in the header (never the last title).
- Company context on non-western employers ("Cafe Bazaar — Iran's largest Android app marketplace (40M+ users)").
- Every experience bullet = CAR (Challenge · Action · Result) with a number.
- Dedicated Tech Stack section, Key Projects section, Certifications, Education, Languages.
- GitHub link in the header of every page (Level-4 proof per the master guide).
- Clean single-column layout, no images for parsing-critical text, accessible typography.
- ATS-parallel language — the same keywords that appear in each CV.

## What's in this folder

```
.
├── index.html               ← landing page that links all 17 portfolios
├── README.md                ← this file
├── .nojekyll                ← forces GitHub Pages to serve raw HTML
├── cv/                      ← all 17 CVs as .docx files
├── 01-marketing-specialist/
│   ├── index.html
│   └── README.md
├── 02-crm-email-marketing/
│   ├── index.html
│   └── README.md
├── 03-seo-content-marketing/
│   ├── index.html
│   └── README.md
├── 04-social-brand-marketing/
│   ├── index.html
│   └── README.md
├── 05-sales-business-development/
│   ├── index.html
│   └── README.md
├── 06-customer-success-support/
│   ├── index.html
│   └── README.md
├── 07-business-analyst/
│   ├── index.html
│   └── README.md
├── 08-data-analyst/
│   ├── index.html
│   └── README.md
├── 09-data-engineer/
│   ├── index.html
│   └── README.md
├── 10-data-scientist/
│   ├── index.html
│   └── README.md
├── 11-ai-ml-engineer/
│   ├── index.html
│   └── README.md
├── 12-software-engineer/
│   ├── index.html
│   └── README.md
├── 13-devops-cloud/
│   ├── index.html
│   └── README.md
├── 14-qa-test-engineer/
│   ├── index.html
│   └── README.md
├── 15-product-project/
│   ├── index.html
│   └── README.md
├── 16-operations-automation/
│   ├── index.html
│   └── README.md
├── 17-finance-accounting/
│   ├── index.html
│   └── README.md
```

## How to publish on GitHub Pages (step-by-step, for your friend)

1. **Create a new GitHub repository.**
   - Go to github.com/new and name it exactly `yheidari.github.io`. Pick **Public**.
   - Because this is a GitHub Pages user site, the repo name must exactly match the GitHub username + `.github.io`.

2. **Upload this folder.**
   - On the new repo page click *"uploading an existing file"*.
   - Drag the entire contents of this folder (every folder + file shown in the tree above) into the browser.
   - Scroll down and click **Commit changes**.

3. **Turn on GitHub Pages.**
   - Click **Settings** → **Pages** (left sidebar).
   - Source: **Deploy from a branch**. Branch: `main` (or `master`). Folder: `/ (root)`. Save.
   - GitHub shows the URL after ~1 minute at `https://yheidari.github.io/`.

4. **Share a specific portfolio.**
   Every portfolio has its own URL — just append the folder name:
   - `…/01-marketing-specialist/`
   - `…/08-data-analyst/`
   - `…/11-ai-ml-engineer/`
   - etc.

   Tip: when applying to a specific role, share only that portfolio URL + the matching CV.

5. **(Optional) Custom domain.**
   - Buy a domain (yasharheidari.com, etc.).
   - In Pages → Custom domain, set the domain and add the CNAME record your registrar instructs.
   - HTTPS is auto-provisioned by GitHub after ~10 minutes.

## Updating a portfolio

Every page is a single `index.html` with inline CSS — no build step, no dependencies. Open the file in any editor, change the text, save, push to GitHub. Pages redeploys in ~30 seconds.

## Why 17 portfolios?

The master guide is explicit: *"350 CVs with the same document = 350 applications optimized for none of them. Each application needs the job description's exact keywords mirrored back."* A dedicated portfolio per industry lets you:

- Send the recruiter a URL where **every word of the page is already the language of their job description**.
- Prove ATS-invisible qualities (design, numbers, clarity) before the human even opens the CV.
- Stand out in a 6-second scan: headline is the **target title**, not your last title.

## Portfolio index

- **Marketing Specialist** → [`01-marketing-specialist/`](./01-marketing-specialist/) · CV: [`cv/01_Yashar_Heidari_Marketing_Specialist_CV.docx`](./cv/01_Yashar_Heidari_Marketing_Specialist_CV.docx)
- **CRM & Email Marketing Specialist** → [`02-crm-email-marketing/`](./02-crm-email-marketing/) · CV: [`cv/02_Yashar_Heidari_CRM_Email_Marketing_Specialist_CV.docx`](./cv/02_Yashar_Heidari_CRM_Email_Marketing_Specialist_CV.docx)
- **SEO & Content Marketing Specialist** → [`03-seo-content-marketing/`](./03-seo-content-marketing/) · CV: [`cv/03_Yashar_Heidari_SEO_Content_Marketing_Specialist_CV.docx`](./cv/03_Yashar_Heidari_SEO_Content_Marketing_Specialist_CV.docx)
- **Social Media & Brand Marketing Specialist** → [`04-social-brand-marketing/`](./04-social-brand-marketing/) · CV: [`cv/04_Yashar_Heidari_Social_Media_Brand_Marketing_Specialist_CV.docx`](./cv/04_Yashar_Heidari_Social_Media_Brand_Marketing_Specialist_CV.docx)
- **Sales & Business Development Specialist** → [`05-sales-business-development/`](./05-sales-business-development/) · CV: [`cv/05_Yashar_Heidari_Sales_Business_Development_Specialist_CV.docx`](./cv/05_Yashar_Heidari_Sales_Business_Development_Specialist_CV.docx)
- **Customer Success & Support Specialist** → [`06-customer-success-support/`](./06-customer-success-support/) · CV: [`cv/06_Yashar_Heidari_Customer_Success_Support_Specialist_CV.docx`](./cv/06_Yashar_Heidari_Customer_Success_Support_Specialist_CV.docx)
- **Business Analyst** → [`07-business-analyst/`](./07-business-analyst/) · CV: [`cv/07_Yashar_Heidari_Business_Analyst_CV.docx`](./cv/07_Yashar_Heidari_Business_Analyst_CV.docx)
- **Data Analyst** → [`08-data-analyst/`](./08-data-analyst/) · CV: [`cv/08_Yashar_Heidari_Data_Analyst_CV.docx`](./cv/08_Yashar_Heidari_Data_Analyst_CV.docx)
- **Data Engineer** → [`09-data-engineer/`](./09-data-engineer/) · CV: [`cv/09_Yashar_Heidari_Data_Engineer_CV.docx`](./cv/09_Yashar_Heidari_Data_Engineer_CV.docx)
- **Data Scientist** → [`10-data-scientist/`](./10-data-scientist/) · CV: [`cv/10_Yashar_Heidari_Data_Scientist_CV.docx`](./cv/10_Yashar_Heidari_Data_Scientist_CV.docx)
- **AI / Machine Learning Engineer** → [`11-ai-ml-engineer/`](./11-ai-ml-engineer/) · CV: [`cv/11_Yashar_Heidari_AI_ML_Engineer_CV.docx`](./cv/11_Yashar_Heidari_AI_ML_Engineer_CV.docx)
- **Software Engineer** → [`12-software-engineer/`](./12-software-engineer/) · CV: [`cv/12_Yashar_Heidari_Software_Engineer_CV.docx`](./cv/12_Yashar_Heidari_Software_Engineer_CV.docx)
- **DevOps / Cloud / Systems Engineer** → [`13-devops-cloud/`](./13-devops-cloud/) · CV: [`cv/13_Yashar_Heidari_DevOps_Cloud_Systems_Engineer_CV.docx`](./cv/13_Yashar_Heidari_DevOps_Cloud_Systems_Engineer_CV.docx)
- **QA / Test Engineer** → [`14-qa-test-engineer/`](./14-qa-test-engineer/) · CV: [`cv/14_Yashar_Heidari_QA_Test_Engineer_CV.docx`](./cv/14_Yashar_Heidari_QA_Test_Engineer_CV.docx)
- **Product & Project Specialist** → [`15-product-project/`](./15-product-project/) · CV: [`cv/15_Yashar_Heidari_Product_Project_Specialist_CV.docx`](./cv/15_Yashar_Heidari_Product_Project_Specialist_CV.docx)
- **Operations & Automation Specialist** → [`16-operations-automation/`](./16-operations-automation/) · CV: [`cv/16_Yashar_Heidari_Operations_Automation_Specialist_CV.docx`](./cv/16_Yashar_Heidari_Operations_Automation_Specialist_CV.docx)
- **Finance & Accounting Analyst** → [`17-finance-accounting/`](./17-finance-accounting/) · CV: [`cv/17_Yashar_Heidari_Finance_Accounting_Analyst_CV.docx`](./cv/17_Yashar_Heidari_Finance_Accounting_Analyst_CV.docx)

---

Based in Messina, Italy · Open to Remote · yashaarheidari@gmail.com
