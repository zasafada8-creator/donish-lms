DONISH — PHONE STARTER (HTML)

Ин версия барои кор бо телефони Android ва GitHub/Vercel омода шудааст.

1) Дар Supabase Project Settings -> API URL ва Publishable key (ё legacy anon key)-ро гиред. Service Role key-ро истифода накунед.
2) Файли index.html-ро дар GitHub repository ҷойгир кунед.
3) Vercel repository-ро import карда deploy мекунад. Барои static HTML одатан project root интихоб мешавад; framework preset-ро Other/None интихоб карда, build command ва output directory-ро холӣ гузоред, агар Vercel талаб накунад.
4) Сайтро кушоед, URL ва key-ро дар блоки «Пайваст кардани Supabase» ворид кунед.
5) Бақайдгирӣ ва воридшавиро санҷед.

ВАЖНО: schema-и мавҷуда танҳо сиёсати ибтидоӣ дорад. Бақайдгирӣ, enrollment ва хондани курсҳоро санҷед. Барои истеҳсолӣ, пеш аз додани иҷозатҳои омӯзгор/Admin ва grading, RLS ва server-side logic бояд такмил дода шаванд.

Ин prototype-и static аст, на маҳсулоти пурра. Курсҳои published хонда мешаванд; сабтином ба enrollments навишта мешавад. Сабти URL/key дар localStorage браузер танҳо дар ҳамин дастгоҳ аст. Key-и public/anon барои истифода дар браузер пешбинӣ шудааст; Service Role key ҳаргиз дар сайт ҷойгир нашавад.
