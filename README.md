This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Prerequisites

1. Python
2. Node.Js
3. Docker

## Getting Started

1. Set up a Python virtual environment:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

2. Install Python dependencies:

   ```bash
   python3 -m pip install -r requirements.txt
   ```

3. Install JavaScript dependencies:

   ```bash
   npm install
   ```

4. Build the Docker image:

   ```bash
   docker build -t python_execution_environment ./docker
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Troubleshooting

1. If you encounter an error saying "Error: Socket hang up," try clicking the "Test Code" button and/or the "Submit" button a couple of times. This is likely due to the image for the Python execution environment not being completely built. Work is in progress to have the image prebuilt or built when loading the website for the first time.

## Future Improvements

1. The user interface (UI) and user experience (UX) can be significantly improved.
2. The database should be migrated to PostgreSQL or another production-grade database (to be researched).
3. The database schemas most likely need to be reworked.
4. Support for a multi-model editor (i.e., multiple files) should be added.
5. Users should be allowed to input their own inputs.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
