# Koronadal Hinugyaw Lions Club — Club Manager

A single-page web app for the Hinugyaw Lions Club to record members, dues, billing,
payments/receipts, invoices, expenses, activities/service projects, minutes of meetings,
and role-based accounts (President/Admin, Treasurer, Secretary, Member).

## Files
- `index.html` — the whole app (open it directly in a browser, or host it as a static site).

## Sign in
A default admin account is created the first time the app runs:
- Username: `admin`
- Password: `admin123`
Change this password immediately after first login (Accounts tab → Edit).

## Notes
This copy was exported from a Claude.ai artifact. Some features (shared multi-user data
sync between officers, and activity photo uploads) only work when the file is running as
a published Claude artifact — opening `index.html` on its own runs it in local/offline mode
using your browser's storage instead, and each browser/device will need to sign in and
build up its own copy of the data. The username/password login itself works the same way
either way, since it's stored in the app's own data alongside everything else.

This login is a convenience layer, not a strong security boundary — anyone with the file
and some technical skill could bypass it or read the stored (hashed) passwords via browser
developer tools. Treat real access control as coming from who you share the file/link with.
