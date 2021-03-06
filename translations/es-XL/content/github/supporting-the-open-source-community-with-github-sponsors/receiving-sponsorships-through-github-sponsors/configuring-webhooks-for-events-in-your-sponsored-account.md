---
title: Configurar webhooks para eventos en tu cuenta patrocinada
intro: Puedes configurar wehbhooks para que te envíen una alerta cuando recibas nuevos patrocinios o cuando los patrocinadores existentes realicen cambios a sus patrocinios.
versions:
  free-pro-team: '*'
redirect_from:
  - /github/supporting-the-open-source-community-with-github-sponsors/configuring-webhooks-for-events-in-your-sponsored-account
---
Para monitorear los cambios a tus patrocinios, tales como las cancelaciones al final de un periodo de pago, puedes crear webhooks para tu cuenta patrocinada de usuario u organización. Cuando estableces un webhook para tu cuenta patrocinada de usuario u organización, recibirás actualizaciones cuando se creen, editen o borren los patrocinios. Para obtener más información, consulta el [evento de webhook de `sponsorship`](/webhooks/event-payloads/#sponsorship).

### Administrar los webhooks para tu cuenta de usuario patrocinada

{% data reusables.sponsors.navigate-to-dev-sponsors-dashboard %}
{% data reusables.sponsors.navigate-to-webhooks-tab %}
{% data reusables.sponsors.add-webhook %}
{% data reusables.sponsors.add-payload-url %}
{% data reusables.sponsors.webhook-content-formatting %}
{% data reusables.sponsors.webhook-secret-token %}
{% data reusables.sponsors.add-active-triggers %}
{% data reusables.sponsors.confirm-add-webhook %}
{% data reusables.sponsors.manage-existing-webhooks %}

### Administrar webhooks para tu cuenta de organización patrocinada

Los propietarios de organización pueden configurar webhooks para sus organizaciones patrocinadas.

{% data reusables.sponsors.navigate-to-org-sponsors-dashboard %}
{% data reusables.sponsors.navigate-to-webhooks-tab %}
{% data reusables.sponsors.add-webhook %}
{% data reusables.sponsors.add-payload-url %}
{% data reusables.sponsors.webhook-content-formatting %}
{% data reusables.sponsors.webhook-secret-token %}
{% data reusables.sponsors.add-active-triggers %}
{% data reusables.sponsors.confirm-add-webhook %}
{% data reusables.sponsors.manage-existing-webhooks %}
