# Setting Up a React Project with Vite and Tailwind CSS

Follow these steps to set up a React project using Vite and Tailwind CSS:

1. **Create a new Vite project:**
    ```sh
    npm create vite@latest my-app --template react
    cd my-app
    npm install
    npm run dev
    ```

2. **Install Tailwind CSS and its dependencies:**
    ```sh
    npm install -D tailwindcss postcss autoprefixer
    npx tailwindcss init
    ```

3. **Configure Tailwind CSS:**
    Update `tailwind.config.js` with the following content:
    ```js
    /** @type {import('tailwindcss').Config} */
    export default {
      content: [
         "./index.html",
         "./src/**/*.{js,ts,jsx,tsx}",
      ],
      theme: {
         extend: {},
      },
      plugins: [],
    };
    ```

4. **Add Tailwind directives to your CSS:**
    Add the following lines at the top of `index.css` in `/src`:
    ```css
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
    ```

5. **Import `index.css` in `main.tsx`:**
    Ensure Tailwind styles are imported by adding this line:
    ```js
    import "./index.css";
    ```

6. **Test Tailwind CSS in `App.tsx`:**
    Replace the content of `App.tsx` with the following code to test Tailwind CSS:
    ```jsx
    function App() {
      return (
         <>
            <div className="min-h-screen bg-gray-100 flex items-center justify-center">
              <h1 className="text-4xl font-bold text-blue-500">Hello, Tailwind CSS!</h1>
            </div>
         </>
      );
    }

    export default App;
    ```

7. **Clean up:**
    - Delete `app.css`.
    - Remove any content from `index.css` that is not from step 4.

8. **Run the development server:**
    ```sh
    npm run dev
    ```
    Check if the `div` and `h1` elements have the Tailwind CSS styles applied.

Now your React project should be set up with Vite and Tailwind CSS!
