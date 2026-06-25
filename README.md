<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Developer Portfolio</title>
</head>
<body style="margin: 0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #f4f7f6; color: #333; line-height: 1.6;">

    <header style="background-color: #1a1a2e; padding: 20px 10%; display: flex; justify-content: space-between; align-items: center; position: sticky; top: 0; z-index: 1000; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
        <div style="color: #00fff0; font-size: 24px; font-weight: bold; letter-spacing: 1px;">&lt;DevProfile /&gt;</div>
        <nav>
            <a href="#about" style="color: #fff; text-decoration: none; margin-left: 20px; font-weight: 500; transition: 0.3s;">About</a>
            <a href="#skills" style="color: #fff; text-decoration: none; margin-left: 20px; font-weight: 500; transition: 0.3s;">Skills</a>
            <a href="#projects" style="color: #fff; text-decoration: none; margin-left: 20px; font-weight: 500; transition: 0.3s;">Projects</a>
            <a href="#contact" style="color: #fff; text-decoration: none; margin-left: 20px; font-weight: 500; transition: 0.3s;">Contact</a>
        </nav>
    </header>

    <section style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%); color: white; padding: 100px 10%; text-align: center;">
        <h1 style="font-size: 48px; margin-bottom: 10px; color: #fff;">Hi, I'm <span style="color: #00fff0;">Your Name</span></h1>
        <p style="font-size: 20px; color: #e2e2e2; max-width: 600px; margin: 0 auto 30px auto;">A passionate Front-End & Back-End Web Developer crafting beautiful, high-performing digital experiences.</p>
        <a href="#projects" style="background-color: #00fff0; color: #1a1a2e; padding: 12px 30px; text-decoration: none; font-weight: bold; border-radius: 25px; box-shadow: 0 4px 15px rgba(0, 255, 240, 0.3);">View My Work</a>
    </section>

    <section id="about" style="padding: 80px 10%; max-width: 900px; margin: 0 auto;">
        <h2 style="text-align: center; font-size: 32px; color: #1a1a2e; margin-bottom: 20px;">About Me</h2>
        <div style="height: 4px; width: 60px; background-color: #00fff0; margin: 0 auto 40px auto; border-radius: 2px;"></div>
        <p style="font-size: 18px; color: #555; text-align: center;">
            I am a web developer specializing in building clean, functional, and user-centered websites. With a strong eye for detail and a knack for problem-solving, I turn complex requirements into elegant code. Let's build something amazing together!
        </p>
    </section>

    <section id="skills" style="background-color: #fff; padding: 80px 10%;">
        <h2 style="text-align: center; font-size: 32px; color: #1a1a2e; margin-bottom: 20px;">My Toolbox</h2>
        <div style="height: 4px; width: 60px; background-color: #00fff0; margin: 0 auto 40px auto; border-radius: 2px;"></div>
        
        <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; max-width: 1000px; margin: 0 auto;">
            <div style="background: #f4f7f6; padding: 15px 30px; border-radius: 8px; font-weight: bold; color: #1a1a2e; border-left: 5px solid #00fff0;">HTML5 / CSS3</div>
            <div style="background: #f4f7f6; padding: 15px 30px; border-radius: 8px; font-weight: bold; color: #1a1a2e; border-left: 5px solid #00fff0;">JavaScript (ES6+)</div>
            <div style="background: #f4f7f6; padding: 15px 30px; border-radius: 8px; font-weight: bold; color: #1a1a2e; border-left: 5px solid #00fff0;">React.js</div>
            <div style="background: #f4f7f6; padding: 15px 30px; border-radius: 8px; font-weight: bold; color: #1a1a2e; border-left: 5px solid #00fff0;">Node.js</div>
            <div style="background: #f4f7f6; padding: 15px 30px; border-radius: 8px; font-weight: bold; color: #1a1a2e; border-left: 5px solid #00fff0;">Git & GitHub</div>
            <div style="background: #f4f7f6; padding: 15px 30px; border-radius: 8px; font-weight: bold; color: #1a1a2e; border-left: 5px solid #00fff0;">Responsive Design</div>
        </div>
    </section>

    <section id="projects" style="padding: 80px 10%;">
        <h2 style="text-align: center; font-size: 32px; color: #1a1a2e; margin-bottom: 20px;">Featured Projects</h2>
        <div style="height: 4px; width: 60px; background-color: #00fff0; margin: 0 auto 40px auto; border-radius: 2px;"></div>

        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; max-width: 1100px; margin: 0 auto;">
            
            <div style="background-color: white; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.05);">
                <div style="background-color: #1a1a2e; height: 180px; display: flex; align-items: center; justify-content: center; color: #00fff0; font-size: 40px;">🛒</div>
                <div style="padding: 20px;">
                    <h3 style="margin-top: 0; color: #1a1a2e;">E-Commerce Platform</h3>
                    <p style="color: #666; font-size: 14px;">A fully functional online store featuring cart management, checkout integration, and responsive layout.</p>
                    <a href="#" style="color: #00fff0; text-decoration: none; font-weight: bold; background-color: #1a1a2e; padding: 8px 16px; border-radius: 4px; display: inline-block; margin-top: 10px;">View Project</a>
                </div>
            </div>

            <div style="background-color: white; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.05);">
                <div style="background-color: #1a1a2e; height: 180px; display: flex; align-items: center; justify-content: center; color: #00fff0; font-size: 40px;">📊</div>
                <div style="padding: 20px;">
                    <h3 style="margin-top: 0; color: #1a1a2e;">Analytics Dashboard</h3>
                    <p style="color: #666; font-size: 14px;">A clean, interactive data visualization dashboard representing complex server metrics seamlessly.</p>
                    <a href="#" style="color: #00fff0; text-decoration: none; font-weight: bold; background-color: #1a1a2e; padding: 8px 16px; border-radius: 4px; display: inline-block; margin-top: 10px;">View Project</a>
                </div>
            </div>

            <div style="background-color: white; border-radius: 8px; overflow: hidden; box-shadow: 0 4px 15px rgba(0,0,0,0.05);">
                <div style="background-color: #1a1a2e; height: 180px; display: flex; align-items: center; justify-content: center; color: #00fff0; font-size: 40px;">💬</div>
                <div style="padding: 20px;">
                    <h3 style="margin-top: 0; color: #1a1a2e;">Real-Time Chat App</h3>
                    <p style="color: #666; font-size: 14px;">An instant messaging app layout utilizing WebSockets for zero-lag communication streams.</p>
                    <a href="#" style="color: #00fff0; text-decoration: none; font-weight: bold; background-color: #1a1a2e; padding: 8px 16px; border-radius: 4px; display: inline-block; margin-top: 10px;">View Project</a>
                </div>
            </div>

        </div>
    </section>

    <section id="contact" style="background-color: #1a1a2e; color: white; padding: 80px 10%; text-align: center;">
        <h2 style="font-size: 32px; margin-bottom: 20px;">Get In Touch</h2>
        <div style="height: 4px; width: 60px; background-color: #00fff0; margin: 0 auto 40px auto; border-radius: 2px;"></div>
        <p style="color: #ccc; max-width: 500px; margin: 0 auto 30px auto;">Interested in working together or just want to say hi? Drop me an email or find me on socials!</p>
        
        <div style="margin-bottom: 30px;">
            <a href="mailto:your.email@example.com" style="color: #00fff0; font-size: 20px; text-decoration: none; font-weight: bold;">your.email@example.com</a>
        </div>
        
        <div>
            <a href="#" style="color: white; margin: 0 10px; text-decoration: none;">GitHub</a> | 
            <a href="#" style="color: white; margin: 0 10px; text-decoration: none;">LinkedIn</a> | 
            <a href="#" style="color: white; margin: 0 10px; text-decoration: none;">Twitter</a>
        </div>
    </section>

    <footer style="background-color: #111122; color: #666; text-align: center; padding: 20px; font-size: 14px;">
        &copy; 2026 Your Name. All Rights Reserved.
    </footer>

</body>
</html>
