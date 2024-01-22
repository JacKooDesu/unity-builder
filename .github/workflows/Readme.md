# Required Secrets

- Build Repo Setting

  - GH_PAT `(if target repo is private)`

  - REPO_NAME `(ex: JacKooDesu/unity-builder)`

- Required by build setting

  - ANDROID_KEYALIAS_NAME `(required if build aab)`

  - ANDROID_KEYALIAS_PASS `(required if build aab)`

  - ANDROID_KEYSTORE_PASS `(required if build aab)`

- Required by [Game-CI](https://game.ci/docs/github/activation)

  - UNITY_EMAIL

  - UNITY_PASSWORD

  - UNITY_LICENSE
  
  - UNITY_SERIAL `(if using pro workflow)`

- Upload Slack

  - SLACK_TOKEN

  - SLACK_CHANNEL_ID
