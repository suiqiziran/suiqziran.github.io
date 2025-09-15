---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>创新科技</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#3B82F6',
                        secondary: '#10B981',
                        dark: '#1F2937',
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .content-auto {
                content-visibility: auto;
            }
            .text-shadow {
                text-shadow: 0 2px 4px rgba(0,0,0,0.1);
            }
        }
    </style>
</head>
<body class="bg-gray-50 font-sans">
    <header class="bg-white shadow-sm">
        <div class="container mx-auto px-4 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-2">
                    <i class="fa fa-lightbulb-o text-primary text-2xl"></i>
                    <h1 class="text-xl font-bold text-dark">创新科技</h1>
                </div>
                
                <nav class="hidden md:flex space-x-6">
                    <a href="#home" class="text-gray-700 hover:text-primary transition-colors">首页</a>
                    <a href="#services" class="text-gray-700 hover:text-primary transition-colors">服务</a>
                    <a href="#products" class="text-gray-700 hover:text-primary transition-colors">产品</a>
                    <a href="#about" class="text-gray-700 hover:text-primary transition-colors">关于我们</a>
                </nav>
                
                <button class="md:hidden text-gray-700" aria-label="菜单">
                    <i class="fa fa-bars text-xl"></i>
                </button>
            </div>
        </div>
    </header>

    <main>
        <section id="home" class="bg-primary text-white py-16">
            <div class="container mx-auto px-4 text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 text-shadow">创新科技，改变未来</h2>
                <p class="text-lg max-w-2xl mx-auto mb-8">我们提供领先的科技解决方案，助力企业创新发展</p>
                <button class="bg-white text-primary px-6 py-2 rounded-md font-medium hover:bg-gray-100 transition-colors">
                    了解更多
                </button>
            </div>
        </section>
        <section id="services" class="py-16 bg-white">
            <div class="container mx-auto px-4">
                <h2 class="text-2xl font-bold text-center mb-12 text-dark">我们的服务</h2>
                
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition-shadow">
                        <div class="text-primary text-3xl mb-4">
                            <i class="fa fa-cogs"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">技术支持</h3>
                        <p class="text-gray-600">专业的技术团队，为您提供全方位的技术支持服务</p>
                    </div>
                    
                    <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition-shadow">
                        <div class="text-primary text-3xl mb-4">
                            <i class="fa fa-cloud"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">云服务</h3>
                        <p class="text-gray-600">高效稳定的云服务解决方案，满足您的业务需求</p>
                    </div>
                    
                    <div class="bg-gray-50 p-6 rounded-lg shadow-sm hover:shadow-md transition-shadow">
                        <div class="text-primary text-3xl mb-4">
                            <i class="fa fa-shield"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">安全防护</h3>
                        <p class="text-gray-600">全方位的安全防护措施，保障您的数据安全</p>
                    </div>
                </div>
            </div>
        </section>
        <section id="products" class="py-16 bg-gray-50">
            <div class="container mx-auto px-4">
                <h2 class="text-2xl font-bold text-center mb-12 text-dark">热门产品</h2>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-md transition-shadow">
                        <img src="https://picsum.photos/600/400?random=1" alt="智能分析系统界面展示" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold mb-2">智能分析系统</h3>
                            <p class="text-gray-600 mb-4">强大的数据分析工具，帮助企业做出明智决策</p>
                            <a href="#" class="text-primary hover:text-primary/80 transition-colors">查看详情</a>
                        </div>
                    </div>
                    
                    <div class="bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-md transition-shadow">
                        <img src="https://picsum.photos/600/400?random=2" alt="物联网管理平台界面展示" class="w-full h-48 object-cover">
                        <div class="p-6">
                            <h3 class="text-xl font-semibold mb-2">物联网管理平台</h3>
                            <p class="text-gray-600 mb-4">高效管理物联网设备，实现智能化控制</p>
                            <a href="#" class="text-primary hover:text-primary/80 transition-colors">查看详情</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="about" class="py-16 bg-white">
            <div class="container mx-auto px-4">
                <h2 class="text-2xl font-bold text-center mb-12 text-dark">关于我们</h2>
                <div class="max-w-3xl mx-auto text-gray-600">
                    <p class="mb-4">创新科技成立于2010年，是一家专注于为企业提供数字化转型解决方案的高科技公司。我们拥有一支由行业专家组成的团队，致力于为客户提供最前沿的技术服务。</p>
                    <p>多年来，我们服务了超过500家企业客户，帮助他们在数字化时代保持竞争力。我们的使命是通过技术创新，推动企业发展，创造更大价值。</p>
                </div>
            </div>
        </section>
    </main>
    <footer class="bg-dark text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center space-x-2 mb-4">
                        <i class="fa fa-lightbulb-o text-primary text-2xl"></i>
                        <h3 class="text-xl font-bold">创新科技</h3>
                    </div>
                    <p class="text-gray-400 mb-4">领先的科技解决方案提供商，助力企业数字化转型</p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-primary transition-colors" aria-label="Facebook">
                            <i class="fa fa-facebook"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-primary transition-colors" aria-label="Twitter">
                            <i class="fa fa-twitter"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-primary transition-colors" aria-label="LinkedIn">
                            <i class="fa fa-linkedin"></i>
                        </a>
                    </div>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">快速链接</h4>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-primary transition-colors">首页</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-primary transition-colors">服务</a></li>
                        <li><a href="#products" class="text-gray-400 hover:text-primary transition-colors">产品</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-semibold mb-4">订阅资讯</h4>
                    <p class="text-gray-400 mb-4">订阅我们的 newsletter，获取最新科技资讯</p>
                    <form class="flex">
                        <input type="email" placeholder="您的邮箱地址" class="px-3 py-2 rounded-l-md w-full focus:outline-none text-gray-800">
                        <button type="submit" class="bg-primary hover:bg-primary/90 text-white px-3 py-2 rounded-r-md transition-colors">
                            <i class="fa fa-paper-plane"></i>
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </footer>

    <script>
        document.querySelector('button').addEventListener('click', function() {
            alert('移动端菜单按钮被点击了！');
        });
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>
    
