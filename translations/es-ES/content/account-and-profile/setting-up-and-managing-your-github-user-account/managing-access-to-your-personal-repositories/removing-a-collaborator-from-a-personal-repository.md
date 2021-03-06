---
title: Eliminar un colaborador de un repositorio personal
intro: 'Cuando eliminas un colaborador de tu proyecto, pierde el acceso de lectura o escritura a tu repositorio. Si el repositorio es privado, y la persona creó una bifurcación, esa bifurcación también se elimina.'
redirect_from:
  - /articles/how-do-i-remove-a-collaborator
  - /articles/what-happens-when-i-remove-a-collaborator-from-my-private-repository
  - /articles/removing-a-collaborator-from-a-private-repository
  - /articles/deleting-a-private-fork-of-a-private-user-repository
  - /articles/how-do-i-delete-a-fork-of-my-private-repository
  - /articles/removing-a-collaborator-from-a-personal-repository
  - /github/setting-up-and-managing-your-github-user-account/removing-a-collaborator-from-a-personal-repository
  - /github/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/removing-a-collaborator-from-a-personal-repository
product: '{% data reusables.gated-features.user-repo-collaborators %}'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Accounts
  - Repositories
shortTitle: Eliminar a un colaborador
---

## Eliminar bifurcaciones de repositorios privados

Aunque se borren las bifurcaciones de los repositorios privados cuando se elimina un colaborador, la persona seguirá teniendo todos los clones locales de tu repositorio.

## Eliminar los permisos de colaborador de una persona que contribuye con un repositorio

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-settings %}
{% ifversion fpt or ghec or ghes > 3.3 or ghae-issue-5658 %}
{% data reusables.repositories.click-collaborators-teams %}
4. Da clic en {% octicon "trash" aria-label="The trash icon" %} a la derecha del colaborador que quieres eliminar. ![Botón para eliminar un colaborador](/assets/images/help/repository/collaborator-remove.png)
{% else %}
3. En la barra lateral izquierda, haz clic en **Collaborators & teams** (Colaboradores y equipos). ![Pestaña Collaborators (Colaboradores)](/assets/images/help/repository/repo-settings-collaborators.png)
4. Al lado del colaborador que deseas eliminar, haz clic en el icono **X**. ![Enlace Remove (Eliminar)](/assets/images/help/organizations/Collaborator-Remove.png)
{% endif %}

## Leer más

- "[Eliminar de un equipo a miembros de la organización](/articles/removing-organization-members-from-a-team)"
- "[Eliminar a un colaborador externo desde el repositorio de una organización](/articles/removing-an-outside-collaborator-from-an-organization-repository)"
