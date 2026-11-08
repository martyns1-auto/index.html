# index.html

<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Nossa História | Árvore Familiar</title>
  <style>
    body{margin:0;background:#f7f5ef;color:#26352d;font:16px system-ui,sans-serif}
    header{background:#244c3b;color:white;padding:20px}
    main{max-width:900px;margin:24px auto;padding:0 16px}
    section,.card{background:white;border:1px solid #dce3dd;border-radius:12px;padding:18px;margin:14px 0}
    label{display:block;margin:12px 0 5px;font-weight:600}
    input,textarea,button{box-sizing:border-box;width:100%;padding:11px;border:1px solid #dce3dd;border-radius:8px;font:inherit}
    button{margin-top:12px;background:#244c3b;color:white;border:0;font-weight:700;cursor:pointer}
    button:disabled{opacity:.6}
    .tabs{display:flex;gap:8px}.tabs button{width:auto;flex:1}
    .secondary{background:#e9f0eb;color:#244c3b}
    .error{color:#a43232}.ok{color:#244c3b}.muted{color:#647168}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px}
    [hidden]{display:none!important}
  </style>
</head>
<body>
  <header>
    <h1>Nossa História</h1>
    Árvore genealógica da família


  </header>

  <main>
    
      <h2>Área da família</h2>
      O acesso aos dados depende de aprovação.


      
        <button id="loginTab" type="button">Entrar</button>
        <button id="signupTab" type="button" class="secondary">Criar cadastro</button>
      


      <form id="authForm">
        
          <label for="fullName">Nome completo</label>
          <input id="fullName" autocomplete="name">
        


        <label for="email">E-mail</label>
        <input id="email" type="email" autocomplete="email" required>
        <label for="password">Senha</label>
        <input id="password" type="password" minlength="6" required>
        <label id="consentField" hidden>
          <input id="consent" type="checkbox">
          Confirmo que estou autorizado(a) a inserir informações familiares.
        </label>
        <button id="authButton" type="submit">Entrar</button>
      </form>
      


    



    
      <h2>Portal da família</h2>
      


      <button id="logout" type="button" class="secondary">Sair</button>
      



      
        
          <h2>Adicionar pessoa</h2>
          <form id="personForm">
            <label for="personName">Nome</label>
            <input id="personName" required>
            <label for="birthDate">Nascimento, se souber</label>
            <input id="birthDate" type="date">
            <label for="deathDate">Falecimento, se aplicável</label>
            <input id="deathDate" type="date">
            <label for="biography">História ou observações</label>
            <textarea id="biography"></textarea>
            <button type="submit">Adicionar pessoa</button>
          </form>
          


          


        



        
          <h2>Adicionar memória</h2>
          <form id="memoryForm">
            <label for="memoryTitle">Título</label>
            <input id="memoryTitle" required>
            <label for="eventDate">Data, se souber</label>
            <input id="eventDate" type="date">
            <label for="story">História</label>
            <textarea id="story" required></textarea>
            <button type="submit">Salvar memória</button>
          </form>
          


          


        


      


    


  </main>
<section style="margin:24px auto;padding:22px;background:#fffdf8;border:1px solid #e5dcc8;border-radius:18px;max-width:900px;font-family:system-ui,sans-serif;color:#24382e">
  <div style="font-size:13px;color:#8a672e;font-weight:700;letter-spacing:.08em">DEMONSTRAÇÃO • NOMES FICTÍCIOS</div>
  <h2 style="margin:8px 0 4px;color:#244c3b">Uma história que atravessa gerações</h2>
  <p style="margin:0 0 20px;color:#647168">Exemplo visual. Estas pessoas não são familiares reais e não foram salvas no banco.</p>

  <h3 style="color:#8a672e">Geração dos avós</h3>
  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:12px">
    <article style="padding:16px;border:1px solid #e5dcc8;border-radius:14px;background:#fbf8f0">
      <div style="font-size:28px">🌿</div><strong>Helena Alves</strong><br><small>Exemplo fictício</small>
    </article>
    <article style="padding:16px;border:1px solid #e5dcc8;border-radius:14px;background:#fbf8f0">
      <div style="font-size:28px">🌿</div><strong>João Alves</strong><br><small>Exemplo fictício</small>
    </article>
  </div>

  <h3 style="color:#8a672e">Geração dos filhos</h3>
  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:12px">
    <article style="padding:16px;border:1px solid #e5dcc8;border-radius:14px;background:#fbf8f0">
      <div style="font-size:28px">🍃</div><strong>Marina Alves</strong><br><small>Exemplo fictício</small>
    </article>
    <article style="padding:16px;border:1px solid #e5dcc8;border-radius:14px;background:#fbf8f0">
      <div style="font-size:28px">🍃</div><strong>Carlos Alves</strong><br><small>Exemplo fictício</small>
    </article>
  </div>

  <h3 style="color:#8a672e">Geração dos netos</h3>
  <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:12px">
    <article style="padding:16px;border:1px solid #e5dcc8;border-radius:14px;background:#fbf8f0">
      <div style="font-size:28px">🌱</div><strong>Ana Alves</strong><br><small>Exemplo fictício</small>
    </article>
    <article style="padding:16px;border:1px solid #e5dcc8;border-radius:14px;background:#fbf8f0">
      <div style="font-size:28px">🌱</div><strong>Pedro Alves</strong><br><small>Exemplo fictício</small>
    </article>
  </div>

  <h3 style="color:#8a672e">Memórias de exemplo</h3>
  <article style="padding:16px;border-left:4px solid #b58b4c;background:#fbf8f0;border-radius:8px">
    <strong>Um almoço de domingo</strong>
    <p style="margin:6px 0 0">Espaço demonstrativo para uma lembrança da família. Este texto é fictício.</p>
  </article>
</section>


  <script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>
  <script>
    const SUPABASE_URL = "https://knafrrqimfbotmgyosuw.supabase.co";
    const SUPABASE_PUBLIC_KEY = "sb_publishable_QrVbXciwHs3j7_QaymaMdQ_NmSij41G";

    const $ = (id) => document.getElementById(id);
    let supabaseClient;
    let signupMode = false;

    function showMessage(id, text, type) {
      const el = $(id);
      el.textContent = text;
      el.className = type || "";
    }

    function startSupabase() {
      if (!window.supabase || !window.supabase.createClient) {
        throw new Error("A biblioteca de conexão não carregou. Recarregue a página.");
      }
      if (SUPABASE_URL.includes("COLE_") || SUPABASE_PUBLIC_KEY.includes("COLE_")) {
        throw new Error("Edite o index.html e preencha a URL e a chave publicável do Supabase.");
      }
      supabaseClient = window.supabase.createClient(
        SUPABASE_URL.trim().replace(/\/+$/, ""),
        SUPABASE_PUBLIC_KEY.trim()
      );
    }

    function setMode(isSignup) {
      signupMode = isSignup;
      $("nameField").hidden = !isSignup;
      $("consentField").hidden = !isSignup;
      $("fullName").required = isSignup;
      $("consent").required = isSignup;
      $("authButton").textContent = isSignup ? "Criar cadastro" : "Entrar";
      $("loginTab").className = isSignup ? "secondary" : "";
      $("signupTab").className = isSignup ? "" : "secondary";
      showMessage("authMessage", "", "");
    }

    $("loginTab").onclick = () => setMode(false);
    $("signupTab").onclick = () => setMode(true);

    function addText(parent, tag, text, className) {
      const el = document.createElement(tag);
      el.textContent = text || "";
      if (className) el.className = className;
      parent.appendChild(el);
    }

    async function refresh() {
      const { data, error } = await supabaseClient.auth.getSession();
      if (error) throw error;

      const session = data.session;
      $("access").hidden = !!session;
      $("family").hidden = !session;
      if (!session) return;

      $("welcome").textContent = "Conta: " + (session.user.email || "");
      $("approvedArea").hidden = true;
      $("approvalMessage").textContent = "Verificando aprovação…";

      const { data: profile, error: profileError } = await supabaseClient
        .from("profiles")
        .select("full_name, approved")
        .eq("id", session.user.id)
        .maybeSingle();

      if (profileError) throw profileError;
      if (!profile) {
        $("approvalMessage").textContent =
          "Perfil não encontrado. Confira se o gatilho de cadastro foi criado no Supabase.";
        return;
      }
      if (!profile.approved) {
        $("approvalMessage").textContent =
          "Cadastro recebido. Aguarde a aprovação do administrador.";
        return;
      }

      $("approvalMessage").textContent = "Acesso aprovado.";
      $("approvedArea").hidden = false;
      await loadFamilyData();
    }

    async function loadFamilyData() {
      const { data: people, error: peopleError } = await supabaseClient
        .from("family_people")
        .select("full_name, birth_date, death_date, biography")
        .order("full_name");
      if (peopleError) throw peopleError;

      const peopleList = $("peopleList");
      peopleList.replaceChildren();
      if (!people.length) addText(peopleList, "p", "Ainda não há pessoas cadastradas.", "muted");

      (people || []).forEach((person) => {
        const card = document.createElement("article");
        card.className = "card";
        addText(card, "h3", person.full_name);
        if (person.birth_date) addText(card, "p", "Nascimento: " + person.birth_date);
        if (person.death_date) addText(card, "p", "Falecimento: " + person.death_date);
        if (person.biography) addText(card, "p", person.biography);
        peopleList.appendChild(card);
      });

      const { data: memories, error: memoriesError } = await supabaseClient
        .from("family_memories")
        .select("title, story, event_date")
        .order("created_at", { ascending: false });
      if (memoriesError) throw memoriesError;

      const memoryList = $("memoryList");
      memoryList.replaceChildren();
      if (!memories.length) addText(memoryList, "p", "Ainda não há memórias cadastradas.", "muted");

      (memories || []).forEach((memory) => {
        const card = document.createElement("article");
        card.className = "card";
        addText(card, "h3", memory.title);
        if (memory.event_date) addText(card, "p", memory.event_date, "muted");
        addText(card, "p", memory.story);
        memoryList.appendChild(card);
      });
    }

    $("authForm").addEventListener("submit", async (event) => {
      event.preventDefault();
      $("authButton").disabled = true;
      showMessage("authMessage", "Processando…", "");

      try {
        if (!supabaseClient) startSupabase();
        const email = $("email").value.trim();
        const password = $("password").value;

        if (signupMode) {
          if (!$("consent").checked) throw new Error("Marque a confirmação para continuar.");
          const { data, error } = await supabaseClient.auth.signUp({
            email,
            password,
            options: { data: { full_name: $("fullName").value.trim() } }
          });
          if (error) throw error;

          if (!data.session) {
            showMessage("authMessage",
              "Cadastro iniciado. Confira seu e-mail para confirmar a conta e depois entre.",
              "ok");
          } else {
            await refresh();
          }
        } else {
          const { error } = await supabaseClient.auth.signInWithPassword({ email, password });
          if (error) throw error;
          await refresh();
        }
      } catch (error) {
        showMessage("authMessage", error.message || "Não foi possível entrar.", "error");
      } finally {
        $("authButton").disabled = false;
      }
    });

    $("logout").onclick = async () => {
      const { error } = await supabaseClient.auth.signOut();
      if (error) showMessage("approvalMessage", error.message, "error");
      else await refresh();
    };

    $("personForm").addEventListener("submit", async (event) => {
      event.preventDefault();
      try {
        const { data: userData, error: userError } = await supabaseClient.auth.getUser();
        if (userError) throw userError;
        const { error } = await supabaseClient.from("family_people").insert({
          full_name: $("personName").value.trim(),
          birth_date: $("birthDate").value || null,
          death_date: $("deathDate").value || null,
          biography: $("biography").value.trim() || null,
          created_by: userData.user.id
        });
        if (error) throw error;
        $("personForm").reset();
        showMessage("personMessage", "Pessoa adicionada.", "ok");
        await loadFamilyData();
      } catch (error) {
        showMessage("personMessage", error.message, "error");
      }
    });

    $("memoryForm").addEventListener("submit", async (event) => {
      event.preventDefault();
      try {
        const { data: userData, error: userError } = await supabaseClient.auth.getUser();
        if (userError) throw userError;
        const { error } = await supabaseClient.from("family_memories").insert({
          title: $("memoryTitle").value.trim(),
          story: $("story").value.trim(),
          event_date: $("eventDate").value || null,
          created_by: userData.user.id
        });
        if (error) throw error;
        $("memoryForm").reset();
        showMessage("memoryMessage", "Memória salva.", "ok");
        await loadFamilyData();
      } catch (error) {
        showMessage("memoryMessage", error.message, "error");
      }
    });

    try {
      startSupabase();
      refresh().catch((error) => showMessage("authMessage", error.message, "error"));
    } catch (error) {
      showMessage("authMessage", error.message, "error");
    }
  </script>
</body>
</html>
