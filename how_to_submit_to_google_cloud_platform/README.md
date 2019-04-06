### Step 1: Download and unzip GCP-PIDP.zip

### Step 2: Initialize
```bash
gcloud init
```

# Update GCP storate in 'submit-gcloud-job.sh' with your google storate location
```bash
   --job-dir=gs://YOUR-GCP-STORAGE 
```

### Step 3: Submit your job (generate job id automatically)
```bash
./submit-gcloud-job.sh
```
