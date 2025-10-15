# GitHub Secrets Configuration Template
# Add these secrets to your GitHub repository settings

## AWS SAA-C03 Source Configuration
```
Secret Name: AWS_SAA_C03_SOURCE_URL
Secret Value: https://github.com/[USERNAME]/[REPOSITORY].git

Secret Name: AWS_SAA_C03_SOURCE_FILE
Secret Value: [PATH_TO_QUESTIONS_FILE]
```

## How to Add Secrets:
1. Go to GitHub repository → Settings → Secrets and variables → Actions
2. Click "New repository secret" 
3. Add each secret with the exact name and your actual values

## Example Values (replace with your actual source):
- SOURCE_URL: https://github.com/[USERNAME]/[REPOSITORY].git
- SOURCE_FILE: [PATH_TO_YOUR_QUESTIONS_FILE]

## Benefits:
- ✅ Source repository kept private
- ✅ No hardcoded URLs in public code
- ✅ Easy to change source without code changes
- ✅ Professional approach to sensitive data