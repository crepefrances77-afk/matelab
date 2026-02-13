import flet as ft
from datetime import datetime

def main(page: ft.Page):
    page.title = "Matelab - Aprenda Matemática"
    page.theme_mode = ft.ThemeMode.LIGHT  # Corrigido: minúsculo 'light'
    page.window_width = 900
    page.window_height = 600
    page.bgcolor = ft.Colors.BLUE_900  # Corrigido: ft.Colors (maiúsculo)
    page.padding = 0
    page.spacing = 0

    # Paleta de cores profissional
    primary_color = ft.Colors.BLUE_900  # Corrigido
    accent_color = ft.Colors.AMBER_400  # Corrigido
    text_color = ft.Colors.WHITE  # Corrigido
    card_color = ft.Colors.WHITE  # Corrigido

    # Cabeçalho
    header = ft.Container(
        content=ft.Row(
            controls=[
                ft.Image(src="logo_matelab.png", width=60, height=60, fit=ft.ImageFit.CONTAIN),
                ft.Text("MATELAB", size=28, weight=ft.FontWeight.BOLD, color=text_color),
            ],
            alignment=ft.MainAxisAlignment.START,
            vertical_alignment=ft.CrossAxisAlignment.CENTER,
            spacing=10,
        ),
        bgcolor=primary_color,
        padding=ft.padding.symmetric(horizontal=20, vertical=10),
        border=ft.border.only(bottom=ft.BorderSide(1, ft.Colors.BLUE_GREY_100)),  # Corrigido
        shadow=ft.BoxShadow(blur_radius=10, spread_radius=2, color=ft.Colors.BLACK26),  # Corrigido
    )

    # Função para atualizar conteúdo principal
    def show_content(content):
        main_content.controls.clear()
        main_content.controls.append(content)
        page.update()

    # Função de login
    def login_view():
        matricula = ft.TextField(
            label="Matrícula", width=300, bgcolor=card_color, border_radius=10, text_size=14
        )
        senha = ft.TextField(
            label="Senha", password=True, can_reveal_password=True, width=300, bgcolor=card_color, border_radius=10
        )
        resultado = ft.Text("", color=text_color, size=14)

        def autenticar(e):
            if matricula.value == "12345" and senha.value == "senha123":
                resultado.value = "✅ Login bem-sucedido! Bem-vindo ao Matelab."
                resultado.color = ft.Colors.GREEN_400  # Corrigido
            else:
                resultado.value = "❌ Matrícula ou senha incorretos. Tente novamente."
                resultado.color = ft.Colors.RED_400  # Corrigido
            page.update()

        return ft.Container(
            content=ft.Column(
                [
                    ft.Text("🔐 Área de Login", size=24, weight=ft.FontWeight.BOLD, color=text_color),
                    matricula,
                    senha,
                    ft.ElevatedButton(
                        "Entrar",
                        bgcolor=accent_color,
                        color=primary_color,
                        on_click=autenticar,
                        style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                    ),
                    resultado,
                ],
                alignment=ft.MainAxisAlignment.CENTER,
                spacing=15,
            ),
            padding=20,
            bgcolor=card_color,
            border_radius=10,
            shadow=ft.BoxShadow(blur_radius=10, spread_radius=1, color=ft.Colors.BLACK26),  # Corrigido
            margin=20,
        )

    # Seções de conteúdo
    historia = ft.Container(
        content=ft.Column(
            [
                ft.Text("📘 História do Matelab", size=24, weight=ft.FontWeight.BOLD, color=primary_color),
                ft.Text(
                    "O Matelab foi criado em 2025 com a missão de tornar a matemática acessível e envolvente. "
                    "Nossa equipe é apaixonada por educação e tecnologia, oferecendo cursos, livros e vídeos "
                    "que transformam números em histórias. Junte-se a nós para explorar o universo da matemática!",
                    selectable=True,
                    size=16,
                    color=primary_color,
                ),
            ],
            spacing=10,
        ),
        padding=20,
        bgcolor=card_color,
        border_radius=10,
        margin=20,
    )

    avisos = ft.Container(
        content=ft.Column(
            [
                ft.Text("📌 Quadro de Avisos", size=24, weight=ft.FontWeight.BOLD, color=primary_color),
                ft.Text("• Novo curso de Cálculo I: Inscrições abertas até 30/10/2025.", color=primary_color),
                ft.Text("• Lançamento do livro 'Matemática Descomplicada' em Novembro.", color=primary_color),
                ft.Text("• Aulas ao vivo toda quarta-feira às 19h. Acesse na aba 'Cursos'.", color=primary_color),
                ft.TextButton(
                    text="📬 Enviar sugestões",
                    url="mailto:contato@matelab.com",
                    style=ft.ButtonStyle(color=accent_color),
                ),
            ],
            spacing=10,
        ),
        padding=20,
        bgcolor=card_color,
        border_radius=10,
        margin=20,
    )

    midia = ft.Container(
        content=ft.Column(
            [
                ft.Text("🎥 Fotos e Vídeos", size=24, weight=ft.FontWeight.BOLD, color=primary_color),
                ft.Image(
                    src="https://picsum.photos/300/200?random=1",
                    width=300,
                    height=200,
                    border_radius=10,
                ),
                ft.Text("Aula introdutória de Álgebra", color=primary_color, size=16),
                ft.TextButton(
                    text="▶️ Assistir vídeo",
                    url="https://www.youtube.com/watch?v=example_video",
                    style=ft.ButtonStyle(color=accent_color),
                ),
                ft.Image(
                    src="https://picsum.photos/300/200?random=2",
                    width=300,
                    height=200,
                    border_radius=10,
                ),
                ft.Text("Resolução de equações", color=primary_color, size=16),
                ft.TextButton(
                    text="▶️ Assistir vídeo",
                    url="https://www.youtube.com/watch?v=example_video2",
                    style=ft.ButtonStyle(color=accent_color),
                ),
            ],
            spacing=15,
        ),
        padding=20,
        bgcolor=card_color,
        border_radius=10,
        margin=20,
    )

    loja = ft.Container(
        content=ft.Column(
            [
                ft.Text("🛒 Loja", size=24, weight=ft.FontWeight.BOLD, color=primary_color),
                ft.Text("Livro: Matemática Descomplicada", color=primary_color, size=16),
                ft.ElevatedButton(
                    "Comprar por R$29,90",
                    bgcolor=accent_color,
                    color=primary_color,
                    on_click=lambda e: page.launch_url("https://buy.stripe.com/example"),
                    style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                ),
                ft.Text("E-book: Fundamentos de Cálculo", color=primary_color, size=16),
                ft.ElevatedButton(
                    "Comprar por R$19,90",
                    bgcolor=accent_color,
                    color=primary_color,
                    on_click=lambda e: page.launch_url("https://buy.stripe.com/example2"),
                    style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                ),
            ],
            spacing=15,
        ),
        padding=20,
        bgcolor=card_color,
        border_radius=10,
        margin=20,
    )

    cursos = ft.Container(
        content=ft.Column(
            [
                ft.Text("🎓 Cursos Online", size=24, weight=ft.FontWeight.BOLD, color=primary_color),
                ft.Text("Curso de Álgebra Linear", color=primary_color, size=16),
                ft.ElevatedButton(
                    "Acessar Curso",
                    bgcolor=accent_color,
                    color=primary_color,
                    on_click=lambda e: page.launch_url("https://example.com/curso-algebra"),
                    style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                ),
                ft.Text("Curso de Cálculo I", color=primary_color, size=16),
                ft.ElevatedButton(
                    "Acessar Curso",
                    bgcolor=accent_color,
                    color=primary_color,
                    on_click=lambda e: page.launch_url("https://example.com/curso-calculo"),
                    style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                ),
            ],
            spacing=15,
        ),
        padding=20,
        bgcolor=card_color,
        border_radius=10,
        margin=20,
    )

    data_atual = ft.Container(
        content=ft.Text(
            f"📅 Data de hoje: {datetime.now().strftime('%d/%m/%Y')}",
            size=16,
            color=primary_color,
        ),
        padding=20,
        bgcolor=card_color,
        border_radius=10,
        margin=20,
    )

    # Menu lateral
    menu = ft.Container(
        content=ft.Column(
            [
                ft.Text("📚 Menu", size=20, weight=ft.FontWeight.BOLD, color=text_color),
                ft.ElevatedButton(
                    "História",
                    bgcolor=accent_color,
                    color=primary_color,
                    on_click=lambda _: show_content(historia),
                    style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                ),
                ft.ElevatedButton(
                    "Avisos",
                    bgcolor=accent_color,
                    color=primary_color,
                    on_click=lambda _: show_content(avisos),
                    style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                ),
                ft.ElevatedButton(
                    "Fotos e Vídeos",
                    bgcolor=accent_color,
                    color=primary_color,
                    on_click=lambda _: show_content(midia),
                    style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                ),
                ft.ElevatedButton(
                    "Loja",
                    bgcolor=accent_color,
                    color=primary_color,
                    on_click=lambda _: show_content(loja),
                    style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                ),
                ft.ElevatedButton(
                    "Cursos",
                    bgcolor=accent_color,
                    color=primary_color,
                    on_click=lambda _: show_content(cursos),
                    style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                ),
                ft.ElevatedButton(
                    "Data Atual",
                    bgcolor=accent_color,
                    color=primary_color,
                    on_click=lambda _: show_content(data_atual),
                    style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                ),
                ft.ElevatedButton(
                    "Login",
                    bgcolor=accent_color,
                    color=primary_color,
                    on_click=lambda _: show_content(login_view()),
                    style=ft.ButtonStyle(shape=ft.RoundedRectangleBorder(radius=10)),
                ),
            ],
            spacing=10,
        ),
        width=250,
        padding=20,
        bgcolor=primary_color,
        border=ft.border.only(right=ft.BorderSide(1, ft.Colors.BLUE_GREY_100)),  # Corrigido
    )

    # Área principal
    main_content = ft.Column(expand=True)

    # Layout geral
    page.add(
        ft.Column(
            [
                header,
                ft.Row(
                    [
                        menu,
                        ft.Container(
                            content=main_content,
                            expand=True,
                            padding=10,
                            bgcolor=ft.Colors.BLUE_800,  # Corrigido
                        ),
                    ],
                    expand=True,
                ),
            ],
            expand=True,
        )
    )

ft.app(target=main)
