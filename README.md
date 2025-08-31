
<!DOCTYPE html>
<!-- saved from url=(0133)https://gensparkpublicblob.blob.core.windows.net/user-upload-image/page/tooluse_XImjnSFrSm2g2NmXzl4haw/mohammad_shadab_portfolio.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohammad Shadab - Data Analyst Portfolio</title>
    <link href="./Mohammad Shadab - Portfolio_files/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="./Mohammad Shadab - Portfolio_files/all.min.css">
    <link href="./Mohammad Shadab - Portfolio_files/css2" rel="stylesheet">
    <style>
        * {
            font-family: 'Inter', sans-serif;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        .data-gradient {
            background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%);
        }
        .teal-gradient {
            background: linear-gradient(135deg, #0d9488 0%, #0f766e 100%);
        }
        .skill-card {
            transition: all 0.3s ease;
            background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%);
        }
        .skill-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .project-card {
            transition: all 0.3s ease;
            background: linear-gradient(135deg, #fefcff 0%, #f8fafc 100%);
        }
        .project-card:hover {
            transform: scale(1.02);
        }
        .education-item {
            position: relative;
        }
        .education-item::before {
            content: '';
            position: absolute;
            left: -8px;
            top: 8px;
            width: 16px;
            height: 16px;
            background: #0891b2;
            border-radius: 50%;
            border: 3px solid white;
            box-shadow: 0 0 0 3px #0891b2;
        }
        .timeline {
            position: relative;
        }
        .timeline::before {
            content: '';
            position: absolute;
            left: 0;
            top: 0;
            bottom: 0;
            width: 2px;
            background: #0891b2;
        }
        .floating-icon {
            animation: float 3s ease-in-out infinite;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }
        .section-divider {
            background: linear-gradient(90deg, transparent, #0891b2, transparent);
            height: 1px;
        }
    </style>
<style id="genspark-badge">
    .genspark-badge-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #333;
      color: white;
      border: none;
      border-radius: 4px;
      padding: 8px 12px;
      font-size: 12px;
      cursor: pointer;
      z-index: 9999;
      display: flex;
      align-items: center;
      gap: 6px;
    }
    
    .genspark-modal {
      display: none;
      position: fixed;
      bottom: 80px;
      right: 20px;
      z-index: 10000;
      justify-content: end;
    }
    
    .genspark-modal-content {
      background-color: white;
      border-radius: 8px;
      max-width: 450px;
      width: 100%;
      box-sizing: border-box;
      padding: 20px;
      position: relative;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      font-size: 14px;
    }
    @media (max-width: 768px) {
      .genspark-modal-content {
        max-width: 90%;
      }
    }
    
    .genspark-close {
      position: absolute;
      top: 10px;
      right: 10px;
      font-size: 20px;
      cursor: pointer;
      background: none;
      border: none;
    }
    
    .genspark-title {
      margin-bottom: 8px;
      font-weight: normal;
      display: inline;
      font-size: 14px;
    }
    
    .genspark-report {
      color: #909499;
      text-decoration: underline;
      cursor: pointer;
      margin-bottom: 14px;
      display: inline;
    }
    
    .genspark-info {
      margin: 25px 0;
      color: #333;
      font-size: 14px;
    }
    
    .genspark-buttons {
      display: flex;
      gap: 10px;
    }
    
    .genspark-remove-btn {
      background-color: #f5f5f5;
      border: 1px solid #ddd;
      color: #333;
      padding: 4px 14px;
      border-radius: 8px;
      cursor: pointer;
      flex: 1;
      font-size: 14px;
      box-sizing: border-box;
    }
    
    .genspark-go-btn {
      background-color: #222;
      border: none;
      color: white;
      padding: 4px 14px;
      border-radius: 8px;
      cursor: pointer;
      flex: 1;
      font-size: 14px;
      box-sizing: border-box;
    }
  </style><style>
    .genspark-notice-dialog {
      display: flex;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.5);
      z-index: 10001;
      align-items: center;
      justify-content: center;
    }

    .genspark-notice-content {
      background-color: white;
      border-radius: 8px;
      max-width: 600px;
      width: 90%;
      box-sizing: border-box;
      padding: 10px 30px 30px 30px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      font-size: 16px;
    }

    .genspark-notice-title {
      color: #000;
      font-family: Arial;
      font-size: 20px;
      font-style: normal;
      font-weight: 700;
      line-height: 150%; 
    }

    .genspark-notice-list {
      margin: 24px 0;
      
      color: #606366;
      font-family: Arial;
      font-size: 14px;
      font-style: normal;
      font-weight: 400;
      line-height: 150%;
      padding-left: 12px;
    }

    .genspark-notice-list li {
      margin-bottom: 12px;
      list-style-type: disc;
    }

    .genspark-notice-list li a {
      color: #606366;
      text-decoration: underline;
    }

    .genspark-notice-checkbox {
      display: flex;
      align-items: center;
      margin-top: 20px;
      gap: 10px;

      color: #232425;

      font-family: Arial;
      font-size: 14px;
      font-style: normal;
      font-weight: 400;
      line-height: normal;
    }

    .genspark-notice-actions {
      display: flex;
      justify-content: center;
      margin-top: 20px;
    }
      
    .genspark-notice-ok {
      color: #232425;

      text-align: center;
      font-family: Arial;
      font-size: 16px;
      font-style: normal;
      font-weight: 700;
      line-height: 150%; 

      cursor: pointer;
      display: flex;
      height: 40px;
      padding: 6px 14px;
      justify-content: center;
      align-items: center;
      gap: 10px;
      align-self: stretch;
      border-radius: 8px;
      border: 1px solid #000;
      box-sizing: border-box;
      width: 100%;
    }
  </style></head>
<body class="bg-gray-50">
    <!-- Hero Section -->
    <section class="gradient-bg text-white py-20 px-6">
        <div class="max-w-6xl mx-auto text-center">
            <div class="mb-8">
                <i class="fas fa-chart-line text-6xl floating-icon mb-6"></i>
                <h1 class="text-5xl font-bold mb-4">Mohammad Shadab</h1>
                <h2 class="text-3xl font-light mb-6">Data Analyst</h2>
                <p class="text-xl max-w-3xl mx-auto leading-relaxed">
                    Aspiring Data Analyst with an MCA degree. Proficient in Power BI, MySQL, Python, MS Excel, and foundational Data Science. 
                    Eager to launch my career in a dynamic organization where I can grow my skills and contribute to data-driven decision-making.
                </p>
            </div>
            <div class="flex justify-center space-x-6 text-lg">
                <div class="flex items-center">
                    <i class="fas fa-envelope mr-2"></i>
                    <span>mohdshadab025@gmail.com</span>
                </div>
                <div class="flex items-center">
                    <i class="fas fa-phone mr-2"></i>
                    <span>9897952262</span>
                </div>
                <div class="flex items-center">
                    <i class="fas fa-map-marker-alt mr-2"></i>
                    <span>Bareilly, India</span>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="py-20 px-6">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">About Me</h2>
            <div class="section-divider mb-12"></div>
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <h3 class="text-2xl font-semibold text-gray-800 mb-6">Professional Background</h3>
                    <p class="text-lg text-gray-600 leading-relaxed mb-6">
                        I am a dedicated and passionate Data Analyst with a Master's degree in Computer Applications. 
                        My expertise spans across various data analysis tools and technologies, enabling me to extract 
                        meaningful insights from complex datasets.
                    </p>
                    <p class="text-lg text-gray-600 leading-relaxed">
                        With proficiency in Power BI, Python, SQL, and Excel, I am committed to transforming raw data 
                        into actionable business intelligence that drives strategic decision-making.
                    </p>
                </div>
                <div class="bg-white p-8 rounded-lg shadow-lg">
                    <h3 class="text-2xl font-semibold text-gray-800 mb-6">Core Interests</h3>
                    <div class="space-y-4">
                        <div class="flex items-center">
                            <i class="fas fa-chart-bar text-blue-500 text-xl mr-4"></i>
                            <span class="text-lg text-gray-700">Data Visualization</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-database text-teal-500 text-xl mr-4"></i>
                            <span class="text-lg text-gray-700">Transforming Data</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-lightbulb text-yellow-500 text-xl mr-4"></i>
                            <span class="text-lg text-gray-700">Extract Insights from Data</span>
                        </div>
                    </div>
                    <div class="mt-8">
                        <h4 class="font-semibold text-gray-800 mb-4">Languages</h4>
                        <div class="space-y-2">
                            <div class="flex justify-between">
                                <span class="text-gray-700">English</span>
                                <span class="text-blue-600 font-medium">Full Professional Proficiency</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-gray-700">Hindi</span>
                                <span class="text-blue-600 font-medium">Full Professional Proficiency</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="py-20 px-6 bg-white">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Technical Skills</h2>
            <div class="section-divider mb-12"></div>
            <div class="grid md:grid-cols-3 lg:grid-cols-6 gap-6">
                <div class="skill-card p-6 rounded-lg text-center border">
                    <i class="fas fa-file-excel text-4xl text-green-600 mb-4"></i>
                    <h3 class="font-semibold text-gray-800">MS Excel</h3>
                </div>
                <div class="skill-card p-6 rounded-lg text-center border">
                    <i class="fas fa-database text-4xl text-blue-600 mb-4"></i>
                    <h3 class="font-semibold text-gray-800">SQL</h3>
                </div>
                <div class="skill-card p-6 rounded-lg text-center border">
                    <i class="fas fa-chart-pie text-4xl text-yellow-600 mb-4"></i>
                    <h3 class="font-semibold text-gray-800">Power BI</h3>
                </div>
                <div class="skill-card p-6 rounded-lg text-center border">
                    <i class="fab fa-python text-4xl text-blue-500 mb-4"></i>
                    <h3 class="font-semibold text-gray-800">Python</h3>
                </div>
                <div class="skill-card p-6 rounded-lg text-center border">
                    <i class="fas fa-table text-4xl text-purple-600 mb-4"></i>
                    <h3 class="font-semibold text-gray-800">Pandas</h3>
                </div>
                <div class="skill-card p-6 rounded-lg text-center border">
                    <i class="fas fa-calculator text-4xl text-red-600 mb-4"></i>
                    <h3 class="font-semibold text-gray-800">NumPy</h3>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section class="py-20 px-6">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Education</h2>
            <div class="section-divider mb-12"></div>
            <div class="max-w-4xl mx-auto">
                <div class="timeline pl-8">
                    <div class="education-item mb-8 p-6 bg-white rounded-lg shadow-lg ml-4">
                        <div class="flex justify-between items-start mb-4">
                            <h3 class="text-xl font-semibold text-gray-800">Master of Computer Application</h3>
                            <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-sm">2023 - 2025</span>
                        </div>
                        <p class="text-gray-600">Abdul Kalam Technical University, Lucknow</p>
                    </div>
                    <div class="education-item mb-8 p-6 bg-white rounded-lg shadow-lg ml-4">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">O Level Diploma</h3>
                        <p class="text-gray-600">NIELIT, Delhi</p>
                    </div>
                    <div class="education-item mb-8 p-6 bg-white rounded-lg shadow-lg ml-4">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">B.Ed Degree</h3>
                        <p class="text-gray-600">MJPRU University, Bareilly</p>
                    </div>
                    <div class="education-item p-6 bg-white rounded-lg shadow-lg ml-4">
                        <h3 class="text-xl font-semibold text-gray-800 mb-2">Bachelor of Science with Mathematics</h3>
                        <p class="text-gray-600">MJPRU University, Bareilly</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Certifications Section -->
    <section class="py-20 px-6 bg-white">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Certifications</h2>
            <div class="section-divider mb-12"></div>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-lg border-l-4 border-blue-500">
                    <i class="fas fa-certificate text-2xl text-blue-600 mb-3"></i>
                    <h3 class="font-semibold text-gray-800 mb-2">Data Analyst</h3>
                    <p class="text-gray-600">Code Square Institution</p>
                </div>
                <div class="bg-gradient-to-br from-yellow-50 to-yellow-100 p-6 rounded-lg border-l-4 border-yellow-500">
                    <i class="fas fa-chart-pie text-2xl text-yellow-600 mb-3"></i>
                    <h3 class="font-semibold text-gray-800 mb-2">Power BI</h3>
                    <p class="text-gray-600">Professional Certification</p>
                </div>
                <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-lg border-l-4 border-blue-500">
                    <i class="fas fa-database text-2xl text-blue-600 mb-3"></i>
                    <h3 class="font-semibold text-gray-800 mb-2">MySQL</h3>
                    <p class="text-gray-600">Database Management</p>
                </div>
                <div class="bg-gradient-to-br from-green-50 to-green-100 p-6 rounded-lg border-l-4 border-green-500">
                    <i class="fab fa-python text-2xl text-green-600 mb-3"></i>
                    <h3 class="font-semibold text-gray-800 mb-2">Python Programming</h3>
                    <p class="text-gray-600">Programming Certification</p>
                </div>
                <div class="bg-gradient-to-br from-green-50 to-green-100 p-6 rounded-lg border-l-4 border-green-500">
                    <i class="fas fa-file-excel text-2xl text-green-600 mb-3"></i>
                    <h3 class="font-semibold text-gray-800 mb-2">MS Excel</h3>
                    <p class="text-gray-600">Advanced Excel Skills</p>
                </div>
                <div class="bg-gradient-to-br from-purple-50 to-purple-100 p-6 rounded-lg border-l-4 border-purple-500">
                    <i class="fas fa-brain text-2xl text-purple-600 mb-3"></i>
                    <h3 class="font-semibold text-gray-800 mb-2">Basic Data Science</h3>
                    <p class="text-gray-600">Foundational Knowledge</p>
                </div>
                <div class="bg-gradient-to-br from-teal-50 to-teal-100 p-6 rounded-lg border-l-4 border-teal-500">
                    <i class="fas fa-analytics text-2xl text-teal-600 mb-3"></i>
                    <h3 class="font-semibold text-gray-800 mb-2">Data Analytics</h3>
                    <p class="text-gray-600">CareerNinja</p>
                </div>
                <div class="bg-gradient-to-br from-indigo-50 to-indigo-100 p-6 rounded-lg border-l-4 border-indigo-500">
                    <i class="fas fa-robot text-2xl text-indigo-600 mb-3"></i>
                    <h3 class="font-semibold text-gray-800 mb-2">Master of ChatGPT</h3>
                    <p class="text-gray-600">AI Tools Certification</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="py-20 px-6">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Projects</h2>
            <div class="section-divider mb-12"></div>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="project-card p-8 rounded-lg shadow-lg border">
                    <div class="flex items-center mb-6">
                        <i class="fas fa-shopping-cart text-3xl text-blue-600 mr-4"></i>
                        <h3 class="text-2xl font-semibold text-gray-800">E-Commerce Data Analysis</h3>
                    </div>
                    <p class="text-gray-600 mb-4">
                        Comprehensive analysis of e-commerce data using Power BI to identify sales trends, 
                        customer behavior patterns, and business insights for strategic decision-making.
                    </p>
                    <div class="flex items-center text-blue-600">
                        <i class="fas fa-tools mr-2"></i>
                        <span class="font-medium">Tools: Power BI</span>
                    </div>
                </div>
                <div class="project-card p-8 rounded-lg shadow-lg border">
                    <div class="flex items-center mb-6">
                        <i class="fas fa-utensils text-3xl text-orange-600 mr-4"></i>
                        <h3 class="text-2xl font-semibold text-gray-800">Swiggy Instamart Data Analysis</h3>
                    </div>
                    <p class="text-gray-600 mb-4">
                        In-depth analysis of Swiggy Instamart delivery data using Python to optimize delivery 
                        routes, analyze customer preferences, and improve operational efficiency.
                    </p>
                    <div class="flex items-center text-orange-600">
                        <i class="fab fa-python mr-2"></i>
                        <span class="font-medium">Tools: Python, Pandas, NumPy</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Workshops Section -->
    <section class="py-20 px-6 bg-white">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-4xl font-bold text-center text-gray-800 mb-12">Workshops &amp; Training</h2>
            <div class="section-divider mb-12"></div>
            <div class="max-w-4xl mx-auto space-y-6">
                <div class="bg-gradient-to-r from-blue-50 to-indigo-50 p-6 rounded-lg border-l-4 border-blue-500">
                    <div class="flex items-center mb-3">
                        <i class="fas fa-robot text-2xl text-blue-600 mr-4"></i>
                        <h3 class="text-xl font-semibold text-gray-800">Master of ChatGPT and AI in Microsoft Office</h3>
                    </div>
                    <p class="text-gray-600">Advanced training on integrating AI tools with Microsoft Office applications for enhanced productivity.</p>
                </div>
                <div class="bg-gradient-to-r from-green-50 to-emerald-50 p-6 rounded-lg border-l-4 border-green-500">
                    <div class="flex items-center mb-3">
                        <i class="fas fa-file-excel text-2xl text-green-600 mr-4"></i>
                        <h3 class="text-xl font-semibold text-gray-800">2 Days Bootcamp of MS Excel Workshop</h3>
                    </div>
                    <p class="text-gray-600">Intensive hands-on training covering advanced Excel features, formulas, and data analysis techniques.</p>
                </div>
                <div class="bg-gradient-to-r from-yellow-50 to-orange-50 p-6 rounded-lg border-l-4 border-yellow-500">
                    <div class="flex items-center mb-3">
                        <i class="fas fa-chart-line text-2xl text-yellow-600 mr-4"></i>
                        <h3 class="text-xl font-semibold text-gray-800">Workshop on Data Visualisation using Power BI</h3>
                    </div>
                    <p class="text-gray-600">Comprehensive workshop focused on creating compelling data visualizations and interactive dashboards.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="data-gradient text-white py-20 px-6">
        <div class="max-w-6xl mx-auto text-center">
            <h2 class="text-4xl font-bold mb-12">Get In Touch</h2>
            <div class="section-divider bg-white/20 mb-12"></div>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="text-center">
                    <i class="fas fa-envelope text-3xl mb-4"></i>
                    <h3 class="font-semibold mb-2">Email</h3>
                    <p class="text-blue-100">mohdshadab025@gmail.com</p>
                </div>
                <div class="text-center">
                    <i class="fas fa-phone text-3xl mb-4"></i>
                    <h3 class="font-semibold mb-2">Phone</h3>
                    <p class="text-blue-100">9897952262</p>
                    <p class="text-blue-100">7599293971</p>
                </div>
                <div class="text-center">
                    <i class="fab fa-linkedin text-3xl mb-4"></i>
                    <h3 class="font-semibold mb-2">LinkedIn</h3>
                    <p class="text-blue-100">linkedin.com/in/mohammad--shadab</p>
                </div>
                <div class="text-center">
                    <i class="fab fa-github text-3xl mb-4"></i>
                    <h3 class="font-semibold mb-2">GitHub</h3>
                    <p class="text-blue-100">github.com/shadab025</p>
                </div>
            </div>
            <div class="mt-12">
                <p class="text-xl text-blue-100 mb-4">Ready to transform data into insights</p>
                <p class="text-lg text-blue-200">Let's collaborate on your next data-driven project!</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8 px-6">
        <div class="max-w-6xl mx-auto text-center">
            <p class="text-gray-400">© 2024 Mohammad Shadab. All rights reserved. | Data Analyst Portfolio</p>
        </div>
    </footer>


    <script id="html_badge_script1">
        window.__genspark_remove_badge_link = "https://www.genspark.ai/api/html_badge/" +
            "remove_badge?token=To%2FBnjzloZ3UfQdcSaYfDtCkVH7qXW6OuWLFDbkJ8M9GQRHKsvx5mfl0HzAlkWbeOoNI9V55jXuUjbvP7KpsId1b7mYNviafaUBvGIwPh4FYTeSKJ1T42mgfrzZeVInEmh8o8%2FPWgbw88gcddBQoPFirc0HZP%2FB8GdroVsHFUpdAT2QSiB4dOKd%2BoOSLqC9MG4ZB2xuSrBVUSHXsHbfFLgHlkipm5MxHh33TfylpxDAkLLcxBbERO9Mc1QEez%2BBZI3SrgFKLEtkGZVlJYCAT1Ng7IqSTfoTpEDbjExTCL2MDrtR6Z8Rrf7P6jqL%2FbzIXxxInBnwv7jzUq8O5QSMxLUYpQDOiSP12AGp1IMRONdxV0tz5q0RINSVhsaV%2BWcRBeib3ztJbvv1JZvPTSdACCGsx5aheX1B2XoMGrEYhyE9MQMmTZ0o99zwS3sy2lDlFpD74NueqcB%2FW1fcnRiGqV%2BpZPumo8QmFGlnCsrwbKMHF%2F1yLNgGgiYNyHfx%2BE3ufAr3LW%2ByPvAvcbwMi%2FZCs7MaJJA89dBkUHEBi8VI6Zbc%3D";
        window.__genspark_locale = "en-US";
        window.__genspark_token = "To/BnjzloZ3UfQdcSaYfDtCkVH7qXW6OuWLFDbkJ8M9GQRHKsvx5mfl0HzAlkWbeOoNI9V55jXuUjbvP7KpsId1b7mYNviafaUBvGIwPh4FYTeSKJ1T42mgfrzZeVInEmh8o8/PWgbw88gcddBQoPFirc0HZP/B8GdroVsHFUpdAT2QSiB4dOKd+oOSLqC9MG4ZB2xuSrBVUSHXsHbfFLgHlkipm5MxHh33TfylpxDAkLLcxBbERO9Mc1QEez+BZI3SrgFKLEtkGZVlJYCAT1Ng7IqSTfoTpEDbjExTCL2MDrtR6Z8Rrf7P6jqL/bzIXxxInBnwv7jzUq8O5QSMxLUYpQDOiSP12AGp1IMRONdxV0tz5q0RINSVhsaV+WcRBeib3ztJbvv1JZvPTSdACCGsx5aheX1B2XoMGrEYhyE9MQMmTZ0o99zwS3sy2lDlFpD74NueqcB/W1fcnRiGqV+pZPumo8QmFGlnCsrwbKMHF/1yLNgGgiYNyHfx+E3ufAr3LW+yPvAvcbwMi/ZCs7MaJJA89dBkUHEBi8VI6Zbc=";
    </script>
    
        <script id="html_badge_script2" src="./Mohammad Shadab - Portfolio_files/html_badge.js.download"></script><button class="genspark-badge-button"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 14 14" fill="none">
<path d="M11.3412 0H2.65879C1.19038 0 0 1.19038 0 2.65879V11.3412C0 12.8096 1.19038 14 2.65879 14H11.3412C12.8096 14 14 12.8096 14 11.3412V2.65879C14 1.19038 12.8096 0 11.3412 0Z" fill="white"></path>
<path d="M11.7403 10.7031H2.29243C2.09641 10.7031 1.9375 10.862 1.9375 11.0581V11.8033C1.9375 11.9993 2.09641 12.1582 2.29243 12.1582H11.7403C11.9363 12.1582 12.0952 11.9993 12.0952 11.8033V11.0581C12.0952 10.862 11.9363 10.7031 11.7403 10.7031Z" fill="#232425"></path>
<path d="M5.09178 9.18166C5.03494 9.18166 4.98695 9.13998 4.97811 9.08314C4.60803 6.63655 4.34025 6.42056 1.91134 6.05427C1.83682 6.0429 1.78125 5.97848 1.78125 5.9027C1.78125 5.82691 1.83682 5.7625 1.91134 5.75113C4.32762 5.3861 4.54235 5.17011 4.90738 2.7551C4.91874 2.68058 4.98316 2.625 5.05894 2.625C5.13473 2.625 5.19914 2.68058 5.21051 2.7551C5.57554 5.17011 5.79153 5.3861 8.20655 5.75113C8.28107 5.7625 8.33664 5.82691 8.33664 5.9027C8.33664 5.97848 8.28107 6.0429 8.20655 6.05427C5.78017 6.42056 5.57302 6.63655 5.20546 9.08314C5.19662 9.13871 5.14862 9.18166 5.09178 9.18166Z" fill="#232425"></path>
<path d="M9.70174 5.949C9.66637 5.949 9.63606 5.92248 9.63101 5.88711C9.39986 4.35878 9.23188 4.22363 7.71492 3.99501C7.66818 3.98743 7.63281 3.94828 7.63281 3.90028C7.63281 3.85355 7.66692 3.81313 7.71492 3.80555C9.2243 3.5782 9.35945 3.44305 9.5868 1.93366C9.59438 1.88693 9.63354 1.85156 9.68153 1.85156C9.72827 1.85156 9.76869 1.88567 9.77627 1.93366C10.0036 3.44305 10.1388 3.5782 11.6482 3.80555C11.6949 3.81313 11.7302 3.85228 11.7302 3.90028C11.7302 3.94702 11.6962 3.98743 11.6482 3.99501C10.1325 4.22363 10.0024 4.35878 9.77247 5.88711C9.76742 5.92248 9.73711 5.949 9.70174 5.949Z" fill="#232425"></path>
<path d="M9.69114 9.76325C9.6684 9.76325 9.64946 9.74683 9.64567 9.7241C9.49915 8.75152 9.39179 8.66563 8.42679 8.52038C8.39648 8.51533 8.375 8.49007 8.375 8.45975C8.375 8.42944 8.39648 8.40418 8.42679 8.39912C9.38673 8.25387 9.47262 8.16798 9.61788 7.20804C9.62293 7.17772 9.64819 7.15625 9.6785 7.15625C9.70882 7.15625 9.73408 7.17772 9.73913 7.20804C9.88439 8.16798 9.97028 8.25387 10.9302 8.39912C10.9605 8.40418 10.982 8.42944 10.982 8.45975C10.982 8.49007 10.9605 8.51533 10.9302 8.52038C9.96523 8.66563 9.88312 8.75152 9.73661 9.7241C9.73282 9.74683 9.71387 9.76325 9.69114 9.76325Z" fill="#232425"></path>
</svg> Made with Genspark</button><div class="genspark-modal">
    <div class="genspark-modal-content">
      <button class="genspark-close"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 14 14" fill="none">
<path d="M11 3L3 11M3 3L11 11" stroke="#232425" stroke-linecap="round" stroke-linejoin="round"></path>
</svg></button>
      <h3 class="genspark-title">This page was created by users with AI.</h3>
      <a class="genspark-report" href="mailto:support@genspark.ai?subject=Report%20inappropriate%20content&amp;body=Current%20URL:%20https://gensparkpublicblob.blob.core.windows.net/user-upload-image/page/tooluse_XImjnSFrSm2g2NmXzl4haw/mohammad_shadab_portfolio.html">Report inappropriate content.</a>
      <p class="genspark-info">Page owner with Plus Plan can remove badge.</p>
      <div class="genspark-buttons">
        <button class="genspark-remove-btn">Remove Badge</button>
        <button class="genspark-go-btn">Go to Genspark</button>
      </div>
    </div>
  </div>
        
    <script id="html_notice_dialog_script" src="./Mohammad Shadab - Portfolio_files/notice_dialog.js.download"></script>
    </body></html>
