# Clinic AI Assistant — test policies site

Static GitHub Pages site for the **testing/demo stage only**.

## Publish

1. Create a **public** GitHub repository named `clinic-ai-assistant` under `idash31-create`.
2. Upload **all four `.html` files** from this folder to the **root** of the repository.
3. Open repository **Settings → Pages → Build and deployment**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`, then **Save**.
5. Once GitHub reports the site as published, verify all three URLs in a private browser window:
   - `https://idash31-create.github.io/clinic-ai-assistant/privacy.html`
   - `https://idash31-create.github.io/clinic-ai-assistant/terms.html`
   - `https://idash31-create.github.io/clinic-ai-assistant/deletion.html`
6. Put those URLs in the corresponding Meta Basic Settings fields, **only after checking they load successfully**.

## Important before publishing
- Review and verify the contact email (`aidsol.co@gmail.com`) can receive and handle deletion/privacy requests.
- Statements describe a **test** environment, not a live clinic. Do not treat as a final legal review.
- When deploying for a real clinic, update the operator/controller identity, medical-data practices, actual service provider terms, concrete retention/deletion arrangements, and applicable legal requirements before collecting real patient data.
- GitHub Pages repo is public. Never place secrets, tokens, patients or private data in it.
