# paas-demo

The sample Odoo repository behind the platform's live demo ("Try the live demo" on the sign-in page). Odoo 18.0.

- `paas_demo/`: installs CRM, Sales and Inventory with a small company's worth of sample data (customers, products,
  opportunities, quotations) and the visitors' Odoo user: login `demo`, password `demo`, a normal user (Sales and CRM
  for all documents, Inventory user; no settings, no app installation). The sample opportunities and quotations are
  theirs, so the default "My Pipeline" / "My Quotations" filters show them.

The demo project is built from this repository's `main` branch as production. Once it has run, take a backup and set
it as the demo's clean state (Admin → Integrations → Live demo): production is restored from it every night.

Made from the platform repository's `deploy/demo/paas-demo/`: change it there and here together.
