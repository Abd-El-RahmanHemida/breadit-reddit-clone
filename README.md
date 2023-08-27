# Breadit - A Modern Fullstack Reddit Clone

Built with the Next.js App Router, TypeScript & Tailwind

## Features

- Infinite scrolling for dynamically loading posts
- Authentication using NextAuth & Google
- Custom feed for authenticated users
- Advanced caching using [Upstash Redis](https://upstash.com/?utm_source=Josh2)
- Optimistic updates for a great user experience
- Modern data fetching using React-Query
- A beautiful and highly functional post editor
- Image uploads & link previews
- Full comment functionality with nested replies

## Getting started

To get started with this project, copy these .env.example variables into a separate .env file:

```bash
DATABASE_URL=
NEXTAUTH_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

REDIS_URL=
REDIS_SECRET=
```

then run

```bash
  yarn dev
```

or

```bash
  npm run dev
```

and that's all you need to get started!

## Acknowledgements

- [Upstash Redis](https://upstash.com/?utm_source=Josh2) for making this possible
- [Code with Antonio](https://www.youtube.com/@codewithantonio) for thumbnail design inspiration
- Shadcn's [Taxonomy respository](https://github.com/shadcn/taxonomy) for showcasing the post editor

## Thanks

Thanks for [Josh](https://www.youtube.com/@joshtriedcoding)

## License

[MIT](https://choosealicense.com/licenses/mit/)
