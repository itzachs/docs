---
title: Einen Pull-Request-Review verwerfen
intro: 'Wenn Dein Repository [Reviews voraussetzt](/articles/about-required-reviews-for-pull-requests), kannst Du Pull-Request-Reviews verwerfen, die nicht mehr gültig sind oder vom Reviewer nicht genehmigt werden können.'
redirect_from:
  - /articles/dismissing-a-pull-request-review
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

{{ site.data.reusables.pull_requests.dismiss_review }}
Dies ändert den Status des Reviews zu einem Review-Kommentar. Wenn Du einen Review verwirfst, musst Du einen Kommentar hinzufügen, in dem Du den Grund für Deine Entscheidung erklärst. Dein Kommentar wird zur Pull-Request-Unterhaltung hinzugefügt.

{{ site.data.reusables.search.requested_reviews_search }}

{{ site.data.reusables.repositories.sidebar-pr }}
{{ site.data.reusables.repositories.choose-pr-review }}{% if currentVersion == "free-pro-team@latest" or currentVersion ver_gt "enterprise-server@2.17" %}
3. Scrolle auf der Registerkarte „Conversation“ (Unterhaltung) zu dem Review, den Du verwerfen möchtest, und klicke dann auf {% octicon "chevron-down" aria-label="The down button" %}. ![Chevron-Symbol (spitze Klammer) im Merge-Feld](/assets/images/help/pull_requests/merge_box/pull-request-open-menu.png)
4. Klicke auf {% octicon "kebab-horizontal" aria-label="The horizontal kebab icon" %} und anschließend auf **Dismiss review** (Review verwerfen). ![3-Punkte-Symbol im Merge-Feld](/assets/images/help/pull_requests/merge_box/pull-request-dismiss-review.png)
5. Gib den Grund für das Verwerfen des Reviews ein, und klicke dann auf **Dismiss review** (Review verwerfen). ![Schaltfläche „Dismiss review" (Verwerfen eines Reviews)](/assets/images/help/pull_requests/merge_box/pull-request-dismiss-review-button.png)
{% else %}
3. Scrolle auf der Registerkarte „Conversation“ (Unterhaltung) zum Review, den Du sehen möchtest, dann klicke auf **Dismiss review** (Review verwerfen). ![Option zum Verwerfen eines Reviews](/assets/images/help/pull_requests/merge_box/pull-request-dismiss-review.png)
4. Gib den Grund für das Verwerfen des Reviews ein, und klicke dann auf **Dismiss review** (Review verwerfen). ![Schaltfläche „Dismiss review" (Verwerfen eines Reviews)](/assets/images/help/pull_requests/merge_box/pull-request-dismiss-review-button.png)
{% endif %}

### Weiterführende Informationen

- „[Informationen zu Pull-Request-Reviews](/articles/about-pull-request-reviews)“
- „[Vorgeschlagene Änderungen in einem Pull Request prüfen](/articles/reviewing-proposed-changes-in-a-pull-request)“
- „[Informationen zu erforderlichen Reviews für Pull Requests](/articles/about-required-reviews-for-pull-requests)“