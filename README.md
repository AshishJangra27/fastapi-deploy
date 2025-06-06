# Streamlit Test App on GCP

## Steps to Run

1. **Build Docker Image**
   ```bash
   docker build -t streamlit-test-app .
   ```

2. **Run Locally**
   ```bash
   docker run -p 8501:8501 streamlit-test-app
   ```

3. **Deploy to GCP**
   - Use Google Cloud Run or GCE
   - Or follow instructions in `gcp_instructions.pdf`