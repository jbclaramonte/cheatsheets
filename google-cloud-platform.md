## Cloud Storage

Stream to output the first 100 bytes

```bash
gsutil cat -r 0-100 gs://path/object
```

Stream to output the last 100 bytes

```bash
gsutil cat -r -100 gs://path/object
```

---

## Manage Configurations

List all local configurations
```bash
gcloud config configurations list
```

In case you want to directly edit configurations, they are stored in the directory:
```bash
~/.config/gcloud/configurations
```