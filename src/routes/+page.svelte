<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>email-frontend</title>
</head>
<body>
  <div id="svelte" class="shadow-lg grid grid-cols-3 gap-8 w-full h-[690px]">
    <section>
      <div>
          <!-- svelte-ignore a11y-missing-attribute -->
          <img src="https://api.dicebear.com/9.x/fun-emoji/svg?seed=Eden">
      </div>
      <div>
        <form action="/search" method="GET">
      
          <div>
            <input type="text" name="busqueda" placeholder="🔍 search contacts..">
          
          </div>
        </form>
      </div>
    </section>
    <section>
      <div>
        <!-- svelte-ignore a11y-missing-attribute -->
        <img src="https://api.dicebear.com/9.x/fun-emoji/svg?seed=Eden">
        <p>Mireya Conner</p>
        <p>Online</p>
      </div>
      <div>
        <input type="submit" id="llamada" name="llamada" value="📞">
        <input type="submit" id="videollamada" name="videollamada" value="📱">
        <input type="submit" id="archivos" name="archivos" value="🗂">
      </div>
    </section>
    <section>
      <div>
        <!-- svelte-ignore a11y-missing-attribute -->
        <img src="https://api.dicebear.com/9.x/fun-emoji/svg?seed=Eden">
        <p>Mireya Conner</p>
        <p>HR Recruiter</p>
      </div>
      <div>
        <p>🌐036 Raynor Fall</p>
        <p>📞(229) 538-1421</p>
        <p>📩Khail_watsica@reed.ca</p>
      </div>
    </section>
  </div>
</body>
</html>