<h1>Create React App Latest (Webpack | TypeScript)</h1>

<p>
  This is project generated to serve as a reproduction starter for Storybook.
</p>

<a  href="https://stackblitz.com/github/storybookjs/sandboxes/tree/next/cra/default-ts/after-storybook?preset=node=">
  View it in Stackblitz
</a>

<h3>Testing instructions</h3>

<p>Install dependencies:</p>
<pre>
  yarn
</pre>

<p>Run Storybook:</p>
<pre>
  yarn storybook
</pre>

# How to reproduce

Create sandbox for latest Create React App and TS. Use storybook 7.4.

Add `storybook.test.ts` to your project.

Run `pnpm test`.

## Note

Also does not work with `npm test`.

# Workaround

Add `"jest-resolve": "^29.6.4"` to resolutions in `package.json`.
