# Changelog

## 1.5.7

- Replace Chromium manifest and notification SVG icons with PNG assets so
  Brave and other Chromium-based browsers can decode them reliably.
- Add the standard 16, 32, 48, and 128 pixel Chromium icon sizes.

## 1.5.6

- Allow a reblog run when exactly one Community is selected.
- Keep the existing confirmation, destination verification, progress, and retry
  safeguards for single-Community runs.
- Use correct singular wording in the confirmation dialog.

## 1.5.5

- Verify the intended Community twice after destination selection.
- Require an explicit destination-confirmed message before navigation can count
  as a successful reblog.
- Stop and retry when Tumblr falls back to the home blog.
- Wait at least five seconds for Tumblr to commit each reblog.
- Pause three seconds before loading the next Community.
- Preserve per-Community success, retry, and failure status locally.

## 1.5.4

- Add a protected delay between Tumblr submissions.

## 1.5.3

- Add background processing, persistent toolbar progress, and retries.
- Prevent the original composer from blocking the background worker.
- Replace broad DOM observation with a lightweight periodic picker check.
