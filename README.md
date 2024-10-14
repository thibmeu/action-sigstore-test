# action-sigstore-test

Testing to upload attestation to sigstore for a worker build.
Build is reproducible, and population the `build` folder, uploading attestation for its content on sigstore public good instance.

To verify locally

```bash
gh attestation verify build/index.js -R thibmeu/action-sigstore-test
```

