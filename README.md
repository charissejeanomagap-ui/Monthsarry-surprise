<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>For You, Love</title>

<style>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background: #1b1124;
    color: white;
}

.slide {
    min-height: 100vh;
    padding: 25px;

    display: flex;
    justify-content: center;
    align-items: center;

    background:
        radial-gradient(circle at 15% 15%, #765394, transparent 30%),
        radial-gradient(circle at 85% 85%, #503366, transparent 30%),
        linear-gradient(135deg, #1b1124, #38244a, #62447b);
}

.card {
    width: 100%;
    max-width: 600px;

    padding: 45px 32px;

    text-align: center;

    background: rgba(255,255,255,0.08);

    border: 1px solid rgba(255,255,255,0.18);

    border-radius: 25px;

    backdrop-filter: blur(15px);

    box-shadow: 0 25px 70px rgba(0,0,0,0.3);

    animation: fadeIn 1s ease;
}

.label {
    font-size: 11px;
    letter-spacing: 4px;
    text-transform: uppercase;

    color: #d5c1e2;

    margin-bottom: 25px;
}

.card h2 {
    font-family: Georgia, serif;

    font-size: 30px;

    font-weight: normal;

    line-height: 1.4;

    margin-bottom: 22px;
}

.card p {
    font-size: 15px;

    line-height: 1.9;

    color: #e9dfef;

    margin-bottom: 25px;
}

.message::first-letter {
    font-family: Georgia, serif;
    font-size: 25px;
}

.next {
    display: inline-block;

    padding: 13px 28px;

    color: white;

    text-decoration: none;

    border: 1px solid rgba(255,255,255,0.35);

    border-radius: 30px;

    background: rgba(255,255,255,0.08);

    transition: 0.4s ease;
}

.next:hover {
    background: rgba(255,255,255,0.18);

    transform: translateY(-3px);
}

.page-number {
    margin-top: 28px;

    font-size: 10px;

    letter-spacing: 3px;

    color: #a995b7;
}

.ready {
    text-align: center;
}

.ready h1 {
    font-family: Georgia, serif;

    font-size: 52px;

    font-weight: normal;

    margin-bottom: 20px;
}

.ready p {
    margin-bottom: 35px;
}

.final {
    min-height: 100vh;

    padding: 80px 25px;

    display: flex;
    justify-content: center;
    align-items: center;

    background:
        radial-gradient(circle at 85% 15%, #8663a3, transparent 30%),
        radial-gradient(circle at 10% 90%, #503267, transparent 30%),
        linear-gradient(135deg, #291637, #63467b);
}

.final-card {
    width: 100%;
    max-width: 700px;

    padding: 45px 32px;

    background: rgba(255,255,255,0.09);

    border: 1px solid rgba(255,255,255,0.2);

    border-radius: 25px;

    backdrop-filter: blur(15px);

    box-shadow: 0 25px 70px rgba(0,0,0,0.3);

    animation: reveal 1.2s ease;
}

.final-label {
    font-size: 11px;

    letter-spacing: 4px;

    text-transform: uppercase;

    color: #d7c3e3;

    margin-bottom: 18px;
}

.final-card h1 {
    font-family: Georgia, serif;

    font-size: 38px;

    font-weight: normal;

    line-height: 1.3;

    margin-bottom: 20px;
}

.line {
    width: 55px;
    height: 1px;

    background: #d5c0e3;

    margin-bottom: 30px;
}

.final-card p {
    font-size: 15px;

    line-height: 1.9;

    color: #eee5f2;

    margin-bottom: 20px;
}

.quote {
    margin: 30px 0;

    padding: 22px;

    border-left: 2px solid #d0b8de;

    background: rgba(255,255,255,0.05);

    font-family: Georgia, serif;

    font-style: italic;

    line-height: 1.8;
}

.signature {
    text-align: center;

    margin-top: 35px;
}

.signature-name {
    font-family: Georgia, serif;

    font-size: 25px;

    margin-top: 8px;
}

@keyframes fadeIn {

    from {
        opacity: 0;
        transform: translateY(25px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }

}

@keyframes reveal {

    from {
        opacity: 0;
        transform: translateY(30px) scale(0.97);
    }

    to {
        opacity: 1;
        transform: translateY(0) scale(1);
    }

}

@media screen and (max-width: 600px) {

    .card {
        padding: 40px 24px;
    }

    .card h2 {
        font-size: 27px;
    }

    .card p {
        font-size: 14px;
    }

    .ready h1 {
        font-size: 45px;
    }

    .final-card {
        padding: 38px 24px;
    }

    .final-card h1 {
        font-size: 30px;
    }

    .final-card p {
        font-size: 14px;
    }

}

</style>
</head>

<body>

<section class="slide" id="one">

    <div class="card">

        <div class="label">
            a little thought
        </div>

        <h2>
            I hope you know how much I appreciate you.
        </h2>

        <p class="message">
            Having you in my life has given me so many
            little moments that I will always be thankful for.
        </p>

        <a href="#two" class="next">
            next →
        </a>

        <div class="page-number">
            01 / 09
        </div>

    </div>

</section>

<section class="slide" id="two">

    <div class="card">

        <div class="label">
            little things
        </div>

        <h2>
            Little moments with you became some of my favorite memories.
        </h2>

        <p class="message">
            Even the simplest conversations and random little
            moments can make an ordinary day feel special.
        </p>

        <a href="#three" class="next">
            next →
        </a>

        <div class="page-number">
            02 / 09
        </div>

    </div>

</section>

<section class="slide" id="three">

    <div class="card">

        <div class="label">
            over time
        </div>

        <h2>
            Over these six months, I've learned so much about us.
        </h2>

        <p class="message">
            We've had happy moments, difficult moments,
            and everything in between, but every part
            has become part of our story.
        </p>

        <a href="#four" class="next">
            next →
        </a>

        <div class="page-number">
            03 / 09
        </div>

    </div>

</section>

<section class="slide" id="four">

    <div class="card">

        <div class="label">
            very thankful
        </div>

        <h2>
            Very thankful for every moment we've shared.
        </h2>

        <p class="message">
            For every laugh, every conversation, every update,
            and every time you made me smile without even trying.
        </p>

        <a href="#five" class="next">
            next →
        </a>

        <div class="page-number">
            04 / 09
        </div>

    </div>

</section>

<section class="slide" id="five">

    <div class="card">

        <div class="label">
            every moment
        </div>

        <h2>
            Every moment with you means something to me.
        </h2>

        <p class="message">
            I may not always say it perfectly,
            but I hope you know that I genuinely
            treasure what we have.
        </p>

        <a href="#six" class="next">
            next →
        </a>

        <div class="page-number">
            05 / 09
        </div>

    </div>

</section>

<section class="slide" id="six">

    <div class="card">

        <div class="label">
            your place
        </div>

        <h2>
            You became someone very special to me.
        </h2>

        <p class="message">
            Someone I can talk to, laugh with,
            share things with, and simply be myself around.
        </p>

        <a href="#seven" class="next">
            next →
        </a>

        <div class="page-number">
            06 / 09
        </div>

    </div>

</section>
<section class="slide" id="seven">

    <div class="card">

        <div class="label">
            one hope
        </div>

        <h2>
            One thing I hope for us is simple.
        </h2>

        <p class="message">
            I hope we continue learning how to understand
            each other, communicate, and grow together.
        </p>

        <a href="#eight" class="next">
            next →
        </a>

        <div class="page-number">
            07 / 09
        </div>

    </div>

</section>

<section class="slide" id="eight">

    <div class="card">

        <div class="label">
            unforgettable
        </div>

        <h2>
            Until now, you still give me so many reasons to smile.
        </h2>

        <p class="message">
            And whenever I look back at everything we've
            shared, I can't help but feel grateful for us.
        </p>

        <a href="#nine" class="next">
            next →
        </a>

        <div class="page-number">
            08 / 09
        </div>

    </div>

</section>

<section class="slide" id="nine">

    <div class="card">

        <div class="label">
            one last thought
        </div>

        <h2>
            Ultimately, I'm just grateful that it is you.
        </h2>

        <p class="message">
            Grateful for the memories, the lessons,
            the laughter, and for these six months
            we've gotten to share.
        </p>

        <a href="#ready" class="next">
            next →
        </a>

        <div class="page-number">
            09 / 09
        </div>

    </div>

</section>

<section class="slide ready" id="ready">

    <div class="card">

        <div class="label">
            one last thing
        </div>

        <h1>
            Ready?
        </h1>

        <p>
            You made it through all of them...
            but there's one more thing I want
            you to see.
        </p>

        <a href="#final" class="next">
            open →
        </a>

    </div>

</section>

<section class="final" id="final">

    <div class="final-card">

        <div class="final-label">
            six months of us
        </div>

        <h1>
            Happy 6th Monthsary, Love.
        </h1>

        <div class="line"></div>

        <p>
            To my Love,
        </p>

        <p>
            Happy 6th monthsary to us.
        </p>

        <p>
            Six months may not seem like forever,
            but for me, these six months already hold
            so many little moments that I will always
            be thankful for.
        </p>

        <p>
            Thank you for staying, for understanding me,
            for making me smile, and for being someone
            I can share my thoughts, stories, and days with.
        </p>

        <p>
            I know we won't always have perfect days.
            There may be moments when things get difficult,
            but I hope we continue choosing each other,
            communicating, understanding, and growing together.
        </p>

        <p>
            I'm grateful for everything we've shared so far,
            and I'm excited for all the memories we still
            have ahead of us.
        </p>

        <div class="quote">
            "Six months with you, and I'm still grateful
            that our paths crossed."
        </div>

        <p>
            Thank you for being you, Love.
            Thank you for being part of my life and
            for giving me so many reasons to smile.
        </p>

        <p>
            Whatever comes next, I hope we continue to be
            patient with each other, understand each other,
            and keep choosing each other.
        </p>

        <p>
            Six months down, hopefully many more to go.
        </p>

        <div class="signature">

            <p>
                I love you, Love.
            </p>

            <div class="signature-name">
                — always, Charisse
            </div>

        </div>

    </div>

</section>


</body>
</html>
