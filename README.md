<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Profile - Sabariana Febriani H.</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        // JavaScript untuk efek fade-in saat scroll
        document.addEventListener('DOMContentLoaded', function() {
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('opacity-100', 'transform', 'translate-y-0');
                    }
                });
            });
            document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
        });
    </script>
</head>
<body class="bg-gradient-to-br from-indigo-500 via-purple-500 to-pink-500 min-h-screen flex items-center justify-center p-4">
    <div class="max-w-5xl mx-auto bg-white rounded-2xl shadow-2xl overflow-hidden transform hover:scale-105 transition-transform duration-300 ease-in-out">
        <!-- Header Section dengan Profile Image -->
        <div class="md:flex relative">
            <div class="md:flex-shrink-0 w-full md:w-1/3 relative">
                <div class="h-64 md:h-full relative">
                    <img src="profil.jpg" alt="Foto Profil"
                    class="with-full h-full object-cover" />
                    <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-50"></div>
                    <div class="absolute bottom-4 left-4 text-white">
                        <h1 class="text-2xl font-bold">Sabariana Febriani H.</h1>
                        <p class="text-lg opacity-90">Software Enthusiast</p>
                    </div>
                </div>
            </div>
            <div class="p-8 md:w-2/3">
                <div class="text-center md:text-left">
                    <h2 class="text-3xl font-extrabold text-gray-800 mb-4">Profil Saya</h2>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        Saat ini saya berada di bangku kelas 10 SMK Negeri 7 Batam, jurusan Pengembangan Perangkat Lunak dan Gim (PPLG). Saya sangat antusias dengan dunia teknologi dan bermimpi untuk menjadi seorang Software Engineer yang berkontribusi dalam membangun aplikasi inovatif. Saya juga sedang mengembangkan keterampilan dan minat yang mendukung profesi yanh saya inginkan.
                    </p>
                    
                    <!-- Biodata Detail in Grid -->
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mt-8">
                        <div class="bg-gray-50 p-4 rounded-lg shadow-md fade-in opacity-0 transform translate-y-4 transition-all duration-1000">
                            <h3 class="text-xl font-semibold text-indigo-600 mb-2 flex items-center">
                                <svg class="w-6 h-6 mr-2" fill="currentColor" viewBox="0 0 20 20"><path d="M10 12a2 2 0 100-4 2 2 0 000 4z"></path><path fill-rule="evenodd" d="M.458 10C1.732 5.943 5.522 3 10 3s8.268 2.943 9.542 7c-1.274 4.057-5.064 7-9.542 7S1.732 14.057.458 10zM14 10a4 4 0 11-8 0 4 4 0 018 0z" clip-rule="evenodd"></path></svg>
                                Hobi
                            </h3>
                            <p class="text-gray-700">Bernyanyi dan memasak – saya suka mengekspresikan diri melalui lagu-lagu penuh semangat dan membuat hidangan lezat untuk keluarga dan teman-teman.</p>
                        </div>
                        
                        <div class="bg-gray-50 p-4 rounded-lg shadow-md fade-in opacity-0 transform translate-y-4 transition-all duration-1000" style="animation-delay: 0.5s;">
                            <h3 class="text-xl font-semibold text-purple-600 mb-2 flex items-center">
                                <svg class="w-6 h-6 mr-2" fill="currentColor" viewBox="0 0 20 20"><path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                                Cita-cita
                            </h3>
                            <p class="text-gray-700">Menjadi Software Engineer profesional yang dapat menciptakan solusi teknologi untuk memudahkan kehidupan sehari-hari.</p>
                        </div>
                        
                        <div class="bg-gray-50 p-4 rounded-lg shadow-md fade-in opacity-0 transform translate-y-4 transition-all duration-1000" style="animation-delay: 1s;">
                            <h3 class="text-xl font-semibold text-pink-600 mb-2 flex items-center">
                                <svg class="w-6 h-6 mr-2" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M18 10c0 3.866-3.582 7-8 7a8.841 8.841 0 01-4.083-.98L2 17l1.338-3.123C2.493 12.767 2 11.434 2 10c0-3.866 3.582-7 8-7s8 3.134 8 7zM7 9H5v2h2V9zm8 0h-2v2h2V9zM9 9h2V7H9v2z" clip-rule="evenodd"></path></svg>
                                Moto Hidup
                            </h3>
                            <p class="text-gray-700">"Belajar dari kesalahan, terus maju" – setiap kesalahan adalah kesempatan untuk tumbuh dan berkembang menjadi lebih baik.</p>
                        </div>
                        
                        <div class="bg-gray-50 p-4 rounded-lg shadow-md fade-in opacity-0 transform translate-y-4 transition-all duration-1000" style="animation-delay: 1.5s;">
                            <h3 class="text-xl font-semibold text-green-600 mb-2 flex items-center">
                                <svg class="w-6 h-6 mr-2" fill="currentColor" viewBox="0 0 20 20"><path d="M10.394 2.08a1 1 0 00-.788 0l-7 3a1 1 0 000 1.84L5.25 8.051a.999.999 0 01.356-.257l4-1.714a1 1 0 11.788 1.84L7.667 9.088l1.94.831a1 1 0 00.787 0l7-3a1 1 0 000-1.84l-7-3zM3.31 9.397L5 10.12v4.102a8.969 8.969 0 00-1.05-.174 1 1 0 01-.89-.89 11.115 11.115 0 01.25-3.762zM9.3 16.573A9.026 9.026 0 007 14.935v-3.957l1.818.78a3 3 0 002.364 0l5.508-2.361a11.026 11.026 0 01.25 3.762 1 1 0 01-.89.89 8.968 8.968 0 00-5.35 2.524 1 1 0 01-1.4 0zM6 18a1 1 0 001-1v-2.065a8.935 8.935 0 00-2-.712V17a1 1 0 001 1z"></path></svg>
                                Pendidikan
                            </h3>
                            <p class="text-gray-700">Kelas 10, SMK Negeri 7 Batam, Jurusan PPLG. Saya aktif belajar pemrograman, desain web, dan pengembangan aplikasi untuk mempersiapkan karir di dunia IT.</p>
                        </div>

                        <!-- New Skills Section -->
                        <div class="bg-gray-50 p-4 rounded-lg shadow-md fade-in opacity-0 transform translate-y-4 transition-all duration-1000 md:col-span-2" style="animation-delay: 2s;">
                            <h3 class="text-xl font-semibold text-blue-600 mb-2 flex items-center">
                                <svg class="w-6 h-6 mr-2" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M3 3a1 1 0 000 2v8a2 2 0 002 2h2.586l-1.293 1.293a1 1 0 101.414 1.414l3-3a1 1 0 000-1.414l-3-3a1 1 0 10-1.414 1.414L7.586 9H5V5a1 1 0 00-1-1z" clip-rule="evenodd"></path><path d="M14 3a1 1 0 000 2h2v8h-2a1 1 0 100 2 1 1 0 000-2z"></path></svg>
                                Keterampilan/Kemampuan
                            </h3>
                            <ul class="text-gray-700 list-disc list-inside leading-relaxed">
                                <li>Bernanyi – Saya mampu menyanyikan beberapa genre lagu dengan penuh emosi dan antusiasme.</li>
                                <li>Memasak – Terampil dalam membuat berbagai hidangan lezat dan seimbang nutrisi.</li>
                                <li>Bermain Basket – Aktif dalam olahraga, meningkatkan koordinasi dan kerjasama.</li>
                                <li>Menguasai Teknik Sempoa – Mahir dalam teknik pertahanan diri yang efisien dan tepat.</li>
                                <li>Sedang Mempelajari Bahasa Pemrograman – Aktif belajar bahasa seperti HTML, CSS, JavaScript, dan lainnya untuk mengembangkan karir di IT.</li>
                            </ul>
                        </div>
                    </div>
                    
                    <!-- Footer Note -->
                    <div class="mt-8 text-center border-t pt-4">
                        <p class="text-gray-500 italic">Terima kasih telah mengunjungi profil saya! Mari berkoneksi dan belajar bersama di dunia teknologi.</p>
                        <button class="mt-4 px-6 py-2 bg-gradient-to-r from-indigo-500 to-purple-500 text-white rounded-full hover:from-purple-500 hover:to-pink-500 transition-all duration-300 shadow-lg" onclick="alert('Terima kasih! Segera hubungi melalui email atau sosial media untuk kolaborasi dan pertukaran ide.')">Hubungi Saya</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
</content>
</create_file>
