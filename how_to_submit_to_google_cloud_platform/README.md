### Step 0: Setup your [Google Cloud Storage](https://cloud.google.com/storage/)

### Step 1: Download files in this folder

### Step 2: Initialize
```bash
gcloud init
```

### Update GCP storate in 'submit-gcloud-job.sh' with your google storate location
```bash
   --job-dir=gs://YOUR-GCP-STORAGE 
```

### Step 3: Submit your job (generate job id automatically)
```bash
./submit-gcloud-job.sh
```
