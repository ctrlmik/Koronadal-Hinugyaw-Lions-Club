# Koronadal Hinugyaw Lions Club — Club Manager

A single-page web app for the Hinugyaw Lions Club to record members, dues, billing,
payments/receipts, invoices, expenses, activities/service projects, minutes of meetings,
and role-based accounts (President/Admin, Treasurer, Secretary, Member).

## Files
- `index.html` — the whole app (open it directly in a browser, or host it as a static site).

## Sign in
A default admin account is created the first time the app ever runs with no saved data:
- Username: `admin`
- Password: `admin123`
Change this password immediately after first login (Accounts tab → Edit).

## Notes
This copy was exported from a Claude.ai artifact. Some features (shared multi-user data
sync between officers so everyone sees the same accounts/records, and activity photo
uploads) only work when the file is running as a published Claude artifact — opening
`index.html` on its own runs it in local/offline mode using your browser's storage instead,
and each browser/device builds up its own separate copy of the data (including its own
"admin"/"admin123" account, seeded fresh in that browser).

The username/password login is a convenience layer, not a strong security boundary —
anyone with the file and some technical skill could bypass it or read the stored (hashed)
passwords via browser developer tools. Treat real access control as coming from who you
share the file/link with.
