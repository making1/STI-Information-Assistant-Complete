# STI Information Assistant
## Start
Windows: double-click `run_windows.bat`.
Linux/macOS: `chmod +x run_linux_mac.sh && ./run_linux_mac.sh`.
Manual alternative: `pip install -r requirements.txt` then `streamlit run app.py`.

The database schema, demo admin, and seed content are initialized automatically if missing.
Demo admin: `admin` / `Admin@12345`. Change this in Admin > Account before deployment.

Seeded English/Kiswahili content is `pending_review`. Only explicitly approved content is learner-visible. The application does not manufacture expert approval. A qualified Kenyan STI clinician/public-health reviewer and Kiswahili health-communication reviewer should approve content before deployment.

The bundled TF-IDF + Logistic Regression intent classifier and tiny bilingual dataset are demonstration components, not research-grade validation. This application is educational, not diagnostic or prescribing software.
