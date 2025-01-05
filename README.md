# Roogle

A community owned search engine, forked from [MiniPerplx](https://github.com/zaidmukaddam/miniperplx).

## Features

- **AI-powered search**: Get answers to your questions using Anthropic's Models.
- **Web search**: Search the web using Tavily's API.
- **URL Specific search**: Get information from a specific URL.
- **Weather**: Get the current weather for any location using OpenWeather's API.
- **Programming**: Run code snippets in multiple languages using E2B's API.
- **Maps**: Get the location of any place using Google Maps API, Mapbox API, and TripAdvisor API.
- **Translation**: Translate text to different languages using Microsoft's Translator API.
- **YouTube Search**: Search for videos on YouTube and get timestamps and transcripts.
- **Academic Search**: Search for academic papers.
- **Product Search**: Search for products on Amazon.
- **X Posts Search**: Search for posts on X.com.
- **Flight Tracker**: Track flights using AviationStack's API.
- **Trending Movies and TV Shows**: Get information about trending movies and TV shows.
- **Movie or TV Show Search**: Get information about any movie or TV show.

## LLM used
- [xAI's Grok](https://x.ai/grok)

## Built with
- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vercel AI SDK](https://sdk.vercel.ai/docs)
- [Shadcn/UI](https://ui.shadcn.com/)
- [Tavily](https://tavily.com/)
- [OpenWeather](https://openweathermap.org/)
- [E2B](https://e2b.dev/)
- [Google Maps](https://developers.google.com/maps)
- [Mapbox](https://www.mapbox.com/)
- [TripAdvisor](https://www.tripadvisor.com/)
- [Microsoft Translator](https://www.microsoft.com/en-us/translator)
- [Exa.AI](https://exa.ai/)
- [AviationStack](https://aviationstack.com/)

### Deploy your own

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FWimbledton%2Froogle&env=XAI_API_KEY,GROQ_API_KEY,TAVILY_API_KEY,OPENWEATHER_API_KEY,E2B_API_KEY&envDescription=API%20keys%20needed%20for%20application)

## Set Roogle as your default search engine

1. **Open your browser settings**:
   - For Chrome: Click the three dots menu → Settings
   - For Firefox: Click the menu button → Settings
   - For Edge: Click the three dots menu → Settings

2. **Navigate to search engine settings**:
   - Chrome: Search engine → Manage search engines
   - Firefox: Search → Default Search Engine → Add search engine
   - Edge: Privacy, search, and services → Address bar and search

3. **Add Roogle**:
   - Search engine: `Roogle`
   - Keyword: `rg`
   - URL: `https://your-deployment-url.com/search?q=%s`

### Local development

To run the example locally you need to:

1. Sign up for accounts with the AI providers you want to use. OpenAI and Anthropic are required, Tavily is required for the web search feature.
2. Obtain API keys for each provider.
3. Set the required environment variables as shown in the `.env.example` file, but in a new file called `.env.local`.
4. `pnpm install` to install the required dependencies.
5. `pnpm dev` to launch the development server.

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details. 