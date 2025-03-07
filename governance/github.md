# Github access permissions and administration

Facilitation roles are identified in [github settings](/.github/settings.yml) which we use for Github admin permissions and managing issues.
Write permissions are enabled by the [GitHub Settings](/.github/settings.yml) file.

There is typically more process for review and collaboration than is controlled by access permissions.
We expect members to review [governance](/governance) and ask questions by filing a Github issue and/or submit suggested changes via Pull Request if anything is not clear.

Chairs have admin privileges and have access to change settings in the Github UI.
Except where noted below, changes should be made in the repo files to control access privileges, not in the Github UI (so they are visible to everyone.)

Note: Members of the CNCF TOC and some CNCF staff also have admin access; however, TAG Roles will be defined transparently using files described below, and will follow TAG processes in making any changes.

## Settings file

Pull Requests to appoint members to new Roles in [github settings](/.github/settings.yml) must be approved by at least one Chair, along with whatever additional required process is defined in [roles](roles.md).
When a member has multiple roles, the role defined later in the file (that does not require additional access) is noted in a comment.
PRs to remove someone from a role must be approved by the person themselves or a majority of Chairs.

## Writing to the main branch

The following settings are controlled in the Github UI by those with admin access.
The "main" branch is "protected" (even for admins), with these requirements:

- can't be deleted
- no direct commits (including no "force push"), also
  - at least one reviewer must approve
  - must be approved by someone listed as a `collaborator` with
    `push` or `admin` access
  - title must not indicate work in
    progress ([WIP](https://github.com/apps/wip))

## Housekeeping

To maintain the main branch in a feasible way the Pull Requests shall come from forked repositories from tag-environmental-sustainability.
After which an unique name should be assigned to identify what will be changed in the forked repository by utilizing branches.

After being merged the branch will be deleted.
Next contributions shall be in another fresh branch.
This way we keep the repository clean and allows a faster acceptance as it's clear what exactly is addressed.
This highly limits the amount of branches and stops having branches around for longer then needed.
