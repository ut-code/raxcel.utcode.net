<script lang="ts">
    import { fade, fly, scale } from "svelte/transition";
</script>

<svelte:head>
    <title>Raxcel - Easy Excel Alternative with AI & R Programming</title>
    <meta
        name="description"
        content="Raxcel (Raku-Excel) - The easiest Excel alternative with AI analysis, R programming, and dynamic charting capabilities."
    />
</svelte:head>

<div
    class="min-h-screen bg-linear-to-br from-blue-500 via-purple-600 to-blue-700"
>
    <!-- Navigation -->
    <div class="navbar bg-base-100/10 backdrop-blur-md fixed top-0 z-50">
        <div class="navbar-start">
            <a class="btn btn-ghost text-xl font-bold text-white" href="/"
                >Raxcel</a
            >
        </div>
        <div class="navbar-end">
            <a
                class="btn btn-ghost text-white hover:text-blue-200"
                href="#features">Features</a
            >
            <a class="btn btn-primary ml-2" href="#download">Download</a>
        </div>
    </div>

    <!-- Hero Section -->
    <div class="hero min-h-screen pt-16">
        <div class="hero-content text-center text-white">
            <div class="max-w-4xl">
                <!-- Floating Icon -->
                <div class="mb-8 animate-bounce">
                    <div
                        class="w-24 h-24 mx-auto bg-white/20 backdrop-blur-md rounded-2xl flex items-center justify-center shadow-2xl"
                    >
                        <svg
                            class="w-12 h-12 text-white"
                            fill="none"
                            stroke="currentColor"
                            viewBox="0 0 24 24"
                        >
                            <path
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                stroke-width="2"
                                d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"
                            ></path>
                        </svg>
                    </div>
                </div>

                <h1
                    class="text-6xl md:text-7xl font-bold mb-6 bg-linear-to-r from-white to-blue-100 bg-clip-text text-transparent drop-shadow-2xl"
                >
                    Raxcel
                </h1>

                <p class="text-2xl md:text-3xl mb-4 font-light">
                    <span class="font-semibold text-blue-200">Raku</span> (easy in
                    Japanese) meets Excel
                </p>

                <p class="text-lg md:text-xl mb-8 opacity-90 max-w-2xl mx-auto">
                    The most intuitive spreadsheet application with AI-powered
                    analysis, embedded R programming, and stunning
                    visualizations
                </p>

                <div id="download">
                    <a
                        href="/"
                        class="btn btn-primary btn-lg text-lg px-8 py-4 shadow-2xl hover:shadow-blue-500/25 transition-all duration-300 hover:scale-105"
                    >
                        <svg
                            class="w-6 h-6 mr-2"
                            fill="none"
                            stroke="currentColor"
                            viewBox="0 0 24 24"
                        >
                            <path
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                stroke-width="2"
                                d="M12 10v6m0 0l-3-3m3 3l3-3m2 8H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"
                            ></path>
                        </svg>
                        Download for Windows
                    </a>
                    <p class="text-sm mt-3 opacity-75">
                        Latest version available on GitHub Releases
                    </p>
                </div>
            </div>
        </div>
    </div>

    <!-- Features Section -->
    <div class="py-20 bg-base-100" id="features">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2
                    class="text-4xl md:text-5xl font-bold mb-4 bg-linear-to-r from-blue-600 to-purple-600 bg-clip-text text-transparent"
                >
                    Powerful Features
                </h2>
                <p class="text-xl text-gray-600 max-w-2xl mx-auto">
                    Experience the future of spreadsheet applications with
                    cutting-edge tools and intuitive design
                </p>
            </div>

            <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">
                <!-- Feature 1: Charts -->
                <div
                    class="card bg-linear-to-br from-blue-50 to-indigo-100 shadow-xl hover:shadow-2xl transition-all duration-300 hover:-translate-y-2"
                >
                    <div class="card-body items-center text-center">
                        <div
                            class="w-16 h-16 bg-blue-500 rounded-full flex items-center justify-center mb-4"
                        >
                            <svg
                                class="w-8 h-8 text-white"
                                fill="none"
                                stroke="currentColor"
                                viewBox="0 0 24 24"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"
                                ></path>
                            </svg>
                        </div>
                        <h3 class="card-title text-2xl text-gray-800 mb-3">
                            Dynamic Charts
                        </h3>
                        <p class="text-gray-600 leading-relaxed">
                            Create stunning, interactive visualizations with our
                            advanced charting engine. From simple bar charts to
                            complex data storytelling.
                        </p>
                    </div>
                </div>

                <!-- Feature 2: AI Analysis -->
                <div
                    class="card bg-linear-to-br from-purple-50 to-pink-100 shadow-xl hover:shadow-2xl transition-all duration-300 hover:-translate-y-2"
                >
                    <div class="card-body items-center text-center">
                        <div
                            class="w-16 h-16 bg-purple-500 rounded-full flex items-center justify-center mb-4"
                        >
                            <svg
                                class="w-8 h-8 text-white"
                                fill="none"
                                stroke="currentColor"
                                viewBox="0 0 24 24"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"
                                ></path>
                            </svg>
                        </div>
                        <h3 class="card-title text-2xl text-gray-800 mb-3">
                            AI-Powered Analysis
                        </h3>
                        <p class="text-gray-600 leading-relaxed">
                            Leverage intelligent agents to automatically
                            discover insights, patterns, and trends in your data
                            with natural language queries.
                        </p>
                    </div>
                </div>

                <!-- Feature 3: R Programming -->
                <div
                    class="card bg-linear-to-br from-green-50 to-emerald-100 shadow-xl hover:shadow-2xl transition-all duration-300 hover:-translate-y-2"
                >
                    <div class="card-body items-center text-center">
                        <div
                            class="w-16 h-16 bg-green-500 rounded-full flex items-center justify-center mb-4"
                        >
                            <svg
                                class="w-8 h-8 text-white"
                                fill="none"
                                stroke="currentColor"
                                viewBox="0 0 24 24"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"
                                ></path>
                            </svg>
                        </div>
                        <h3 class="card-title text-2xl text-gray-800 mb-3">
                            Embedded R Language
                        </h3>
                        <p class="text-gray-600 leading-relaxed">
                            Execute powerful R scripts directly within your
                            spreadsheets for advanced statistical analysis and
                            data science workflows.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- CTA Section -->
    <div class="py-20 bg-linear-to-r from-blue-600 to-purple-600 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-6">
                Ready to Transform Your Data Experience?
            </h2>
            <p class="text-xl mb-8 opacity-90 max-w-2xl mx-auto">
                Join thousands of users who have already revolutionized their
                workflow with Raxcel's powerful features.
            </p>
            <a
                href="#download"
                class="btn btn-primary btn-lg bg-white text-blue-600 hover:bg-gray-100 border-none shadow-xl hover:scale-105 transition-transform duration-300"
            >
                Get Started Today
            </a>
        </div>
    </div>

    <!-- Footer -->
    <footer class="footer footer-center p-10 bg-base-200 text-base-content">
        <aside>
            <div class="font-bold text-lg">Raxcel</div>
            <p class="text-gray-600">
                Making data analysis accessible and powerful for everyone.
            </p>
            <p class="text-sm text-gray-500">
                Built with ❤️ for the data community
            </p>
        </aside>
    </footer>
</div>
