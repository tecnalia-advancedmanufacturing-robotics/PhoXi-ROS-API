> [!WARNING]
> **This repository has moved.**
>
> `photoneo/PhoXi-ROS-API` will become **private on 16-November-2026** and will no longer receive updates.
> Development continues in the new public repository:
>
> ### 👉 [github.com/photoneo-3d/PhoXi-ROS-API](https://github.com/photoneo-3d/PhoXi-ROS-API)
>
> Existing forks of this repository will not be updated. Issues and pull requests are not migrated.
>
> #### Migration steps
>
> 1. **Fork the new repository** on GitHub: `photoneo-3d/PhoXi-ROS-API`.
> 2. **Point your local clone to the new fork** and add the Photoneo repository as `upstream`:
>    ```bash
>    git remote set-url origin https://github.com/<your-account>/PhoXi-ROS-API.git
>    git remote add upstream https://github.com/photoneo-3d/PhoXi-ROS-API.git
>    git fetch origin
>    git fetch upstream
>    ```
> 3. **Re-apply your changes** on top of `upstream/main`. The new repository is a ROS 2 driver, so its code and history may differ from this one:
>    ```bash
>    git checkout -b my-changes upstream/main
>    git cherry-pick <your-commit-hashes>   # or apply your changes manually
>    ```
> 4. **Check the result** against the new code: build it and make sure your changes still work.
> 5. **Push and open a pull request** if you want your changes included. Direct pushes to `main` are not possible; changes are merged via pull request after review.
>    ```bash
>    git push origin my-changes
>    ```
> 6. **Delete the old fork** once you have moved everything.
>
---
