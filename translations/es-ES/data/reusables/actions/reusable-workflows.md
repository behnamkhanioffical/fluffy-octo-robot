{% ifversion fpt or ghes > 3.3 or ghae-issue-4757 or ghec %}

{% ifversion ghes or ghec or ghae %}You can share workflows with your organization, publicly or privately, by calling{% else %} You can call{% endif %} one workflow from within another workflow. Esto te permite reutilizar flujos de trabajo, evitando la duplicación y haciendo que tus flujos se puedan mantener mejor. Para obtener más información, consulta la sección "[Reutilizar flujos de trabajo](/actions/learn-github-actions/reusing-workflows)".
{% endif %}
