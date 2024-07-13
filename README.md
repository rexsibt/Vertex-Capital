<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vertex Capital</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 text-gray-900">

    <!-- Header -->
    <header class="bg-white shadow">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="flex items-center">
                <img src="logo.webp" alt="Vertex Capital Logo" class="h-10 mr-2">
                <span class="text-2xl font-bold text-gray-800">Vertex Capital</span>
            </a>
            <nav class="flex space-x-4">
                <a href="#home" class="text-gray-700 hover:text-gray-900">主页</a>
                <a href="#about" class="text-gray-700 hover:text-gray-900">关于我们</a>
                <a href="#services" class="text-gray-700 hover:text-gray-900">服务</a>
                <a href="#contact" class="text-gray-700 hover:text-gray-900">联系</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="bg-gray-900 text-white h-screen flex items-center justify-center">
        <div class="text-center">
            <h1 class="text-4xl font-bold mb-4">欢迎来到 Vertex Capital</h1>
            <p class="text-lg mb-8">您的短期贷款合作伙伴</p>
            <a href="#services" class="bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-500">了解更多</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="container mx-auto px-6 py-16">
        <div class="text-center">
            <h2 class="text-3xl font-bold mb-4">关于我们</h2>
            <p class="text-lg text-gray-700">Vertex Capital 是一家领先的金融咨询公司，致力于帮助客户实现他们的财务目标。我们的专家团队提供个性化的财务规划和投资策略，以确保长期成功。</p>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="bg-gray-200 py-16">
        <div class="container mx-auto px-6">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold">我们的服务</h2>
                <p class="text-lg text-gray-700">我们提供广泛的金融服务，以满足您的需求。</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-white p-6 rounded shadow">
                    <h3 class="text-xl font-bold mb-4">短期贷款</h3>
                    <p class="text-gray-700">灵活的短期贷款解决方案，帮助您实现财务目标。</p>
                </div>
                <div class="bg-white p-6 rounded shadow">
                    <h3 class="text-xl font-bold mb-4">财务规划</h3>
                    <p class="text-gray-700">全面的财务规划，帮助您实现目标。</p>
                </div>
                <div class="bg-white p-6 rounded shadow">
                    <h3 class="text-xl font-bold mb-4">投资管理</h3>
                    <p class="text-gray-700">专家的投资管理，助您财富增长。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Loan Application Section -->
    <section id="apply" class="container mx-auto px-6 py-16">
        <div class="text-center mb-12">
            <h2 class="text-3xl font-bold">申请贷款</h2>
            <p class="text-lg text-gray-700">填写下面的表格，快速申请短期贷款。</p>
        </div>
        <div class="max-w-md mx-auto bg-white p-6 rounded shadow">
            <form>
                <div class="mb-4">
                    <label class="block text-gray-700">姓名</label>
                    <input type="text" class="w-full px-4 py-2 border rounded focus:outline-none focus:border-blue-500">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700">电子邮件</label>
                    <input type="email" class="w-full px-4 py-2 border rounded focus:outline-none focus:border-blue-500">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700">贷款金额</label>
                    <input type="number" class="w-full px-4 py-2 border rounded focus:outline-none focus:border-blue-500">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700">贷款期限（以月为单位）</label>
                    <input type="number" class="w-full px-4 py-2 border rounded focus:outline-none focus:border-blue-500">
                </div>
                <button type="submit" class="bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-500">申请</button>
            </form>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container mx-auto px-6 py-16">
        <div class="text-center mb-12">
            <h2 class="text-3xl font-bold">联系我们</h2>
            <p class="text-lg text-gray-700">与我们联系，开始您的财务旅程。</p>
        </div>
        <div class="max-w-md mx-auto bg-white p-6 rounded shadow">
            <form>
                <div class="mb-4">
                    <label class="block text-gray-700">姓名</label>
                    <input type="text" class="w-full px-4 py-2 border rounded focus:outline-none focus:border-blue-500">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700">电子邮件</label>
                    <input type="email" class="w-full px-4 py-2 border rounded focus:outline-none focus:border-blue-500">
                </div>
                <div class="mb-4">
                    <label class="block text-gray-700">消息</label>
                    <textarea class="w-full px-4 py-2 border rounded focus:outline-none focus:border-blue-500"></textarea>
                </div>
                <button type="submit" class="bg-blue-600 text-white py-2 px-4 rounded hover:bg-blue-500">发送</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-6">
        <div class="container mx-auto text-center">
            <p>&copy; 2024 Vertex Capital. 版权所有。</p>
            <div class="flex justify-center space-x-4 mt-4">
                <a href="#" class="hover:text-gray-400">Facebook</a>
                <a href="#" class="hover:text-gray-400">Twitter</a>
                <a href="#" class="hover:text-gray-400">LinkedIn</a>
            </div>
        </div>
    </footer>

</body>
</html>
