# Add your instructional videos here

The video catalog in `src/App.tsx` points to files in this folder.

To add a lesson:

1. Put the `.mp4` file in this folder.
2. Copy the small catalog entry in `src/App.tsx`.
3. Change the `title` and `source` values.

Example:

```ts
{ title: 'New lesson name', source: './code/new-lesson.mp4' },
```