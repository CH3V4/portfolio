# Notifier

**Problem**

High and critical severity cases need to reach the right people fast — especially outside business hours when an on-call analyst may not be actively watching the SIEM. If the primary notification system fails, there is no fallback, meaning a critical case could sit unacknowledged and breach SLA without anyone being aware.

**Solution**

A backup notification service that independently monitors for high and critical cases and delivers alerts via Email, Microsoft Teams, and Telegram. It operates as a safety net — if the primary notifier is down or misses an alert, this service ensures the notification still gets through. It can be used for SLA breach warnings, on-call paging, or both.

**Impact**

Eliminated the single point of failure in the alert notification chain. Critical cases now have a guaranteed delivery path regardless of the state of the primary notifier, ensuring on-call analysts are always reached and SLA obligations are protected.

<!-- ![Notifier — sample](screenshots/overview.png) -->
