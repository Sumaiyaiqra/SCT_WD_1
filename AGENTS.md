<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

## Application structure
- Keep the food-menu experience on the index route with section anchors and client-side category filtering; this keeps the fixed navigation coherent across the single-page experience.
- Define visual styles and colors in src/styles.css and use shared Button variants for controls; this keeps presentation consistent.
