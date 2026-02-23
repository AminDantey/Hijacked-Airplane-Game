# Hijacked-Airplane-Game
Unity AI pursuit prototype with dynamic fear-based behavior system:

EN Description:
This project is a Unity gameplay prototype focused on designing an AI-driven pursuit system built around a dynamic Fear Level mechanic.

The player controls a military jet chasing a hijacked passenger aircraft. The objective is not to destroy the target, but to force it into an emergency landing through controlled psychological pressure.

Core Gameplay Mechanics

The target aircraft operates with two main parameters:

Health (HP) – physical damage level

Fear Level – pilot psychological pressure level

Fear increases dynamically based on projectile and missile proximity. Three distance tiers determine the intensity of fear gain. Missiles generate significantly more fear than standard bullets.

As Fear Level rises:

The aircraft increases speed

Evasive maneuvers become more aggressive

AI behavior becomes more unstable and reactive

If no threat occurs for a short duration, Fear gradually decays over time.

Surrender State

When Fear Level reaches 100%, the aircraft enters a surrender phase.
The player must maintain Fear between 95% and 100% for 4 seconds. During this window, the aircraft slows down and initiates emergency landing.

If Fear drops below 95% before the timer completes, the aircraft regains control and resumes escape behavior.

Loss Conditions

Destroying the target (HP reaches zero or direct missile impact)

Collision or excessive proximity

Overtaking the target

Mission time-out

Project Purpose

This prototype focuses on:

State-based AI behavior design

Psychological pressure mechanics instead of pure destruction

Dynamic balance between speed, fear, and aggression

Win/Loss state management

Visuals are intentionally simple (Low-Poly), as the main focus is gameplay systems and behavioral logic.

FA Description:
این پروژه یک پروتوتایپ گیم‌پلی در یونیتی است که تمرکز آن بر طراحی مکانیک‌های تعقیب هوایی و سیستم رفتاری مبتنی بر «Fear Level» می‌باشد.

در این بازی، بازیکن با یک جت نظامی در حال تعقیب یک هواپیمای مسافربری ربوده‌شده است. هدف نابود کردن هواپیما نیست، بلکه وادار کردن آن به فرود اضطراری از طریق ایجاد فشار روانی کنترل‌شده است.

مکانیک اصلی بازی

هواپیمای هدف دارای دو پارامتر اصلی است:

Health (HP) – میزان آسیب فیزیکی

Fear Level – سطح ترس خلبان

سیستم ترس به صورت داینامیک بر اساس نزدیکی شلیک تیر یا انفجار موشک افزایش می‌یابد. سه سطح فاصله برای محاسبه شدت ترس در نظر گرفته شده است. موشک‌ها تأثیر روانی بیشتری نسبت به تیر معمولی دارند.

با افزایش Fear Level:

سرعت هواپیما افزایش می‌یابد

مانورهای تهاجمی و حرکات ناگهانی بیشتر می‌شود

رفتار AI حالت تهاجمی‌تری می‌گیرد

در صورت عدم وجود تهدید برای چند ثانیه، سطح ترس به‌تدریج کاهش می‌یابد (Fear Decay).

حالت تسلیم (Surrender State)

اگر Fear Level به 100٪ برسد، هواپیما وارد فاز تسلیم می‌شود.
بازیکن باید به مدت ۴ ثانیه سطح ترس را در بازه 95٪ تا 100٪ حفظ کند. در این حالت سرعت هواپیما کاهش یافته و در صورت حفظ فشار، فرود اضطراری انجام شده و بازی با پیروزی به پایان می‌رسد.

در صورت کاهش Fear Level به زیر 95٪ پیش از پایان زمان، هواپیما مجدداً اقدام به فرار می‌کند.

شرایط شکست

نابود کردن هواپیما (کاهش HP به صفر یا برخورد مستقیم موشک)

برخورد فیزیکی یا نزدیک شدن بیش از حد

سبقت گرفتن از هدف

اتمام زمان ماموریت

هدف پروژه

این پروژه با تمرکز بر:

طراحی سیستم حالت‌ها (State-Based Behavior)

پیاده‌سازی مکانیزم فشار روانی به‌جای تخریب مستقیم

بالانس پویا بین سرعت، ترس و رفتار AI

مدیریت شرایط برد و باخت

توسعه داده شده است.

گرافیک پروژه ساده و Low-Poly بوده و تمرکز اصلی بر منطق گیم‌پلی و رفتار سیستم‌ها است.

