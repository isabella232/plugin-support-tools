# Plugin Support Tools

## Insomnia request collection

### How to import

1. Download the `collection.json`
1. Open Insomnia, go to `Preferences` -> `Data` -> `Import Data` -> `From File`
1. Switch to the `Support` workspace, open `Manage Environments`
1. Fill the values or create a `Sub-Environment` based on the `Base Environment`

## Sample CSV
1. Run `npx serve` to serve the root dir on `http://localhost:5000`
1. Run `ngrok http 5000` to expose local server