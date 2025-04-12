<script>
    import Link from "/src/components/Link.svelte"
</script>

<div class="top-bar">
    <div class="concluded">
        <p>Hexa Falls 2025 is yet to begin. Can sign up for updates and information from us <a onclick="fathom.trackEvent('interest form');" href="https://form.typeform.com/to/TVIkfLtK?utm_source=hackaustin.net">here!</a></p>
    </div>
    <nav>
        <h2 class="mono primary-green">HEXA<span class="space"></span>FALLS!</h2>
        <div class="button-box">
            <Link target="https://bank.hackclub.com/donations/start/hackaustin">Sponsor</Link>
            <span class="button"><a onclick="fathom.trackEvent('interest form');" href="discord.com/channels/1358373328422834246/1358373329064427646">Get updates!</span>
        </div>


    </nav>
</div>

<style>
    
    .top-bar {
        position: fixed;
        display: flex;
        top: 0;
        z-index: 1;
        flex-direction: column;
    }
    
    .concluded {
        width: 100%;
        background-color: #cdba8a;
        height: max-content;
    }
    
    .concluded > p {
       margin: 0;
       text-align: center;
       font-weight: 500;
       padding: 0.5rem;
    }
    
    nav {
        background-color: black;
        height: max-content;
        width: 100vw;
        top: 0;
        padding:0.5rem;
        padding-right: 2rem;
        box-sizing: border-box; 
        line-height: 2rem;
        color: white;
        align-items: center;
        z-index: 1;
    }
    
    .button > a {
        color: black;
    }
    
    a {
        text-decoration: none;
        font-weight: 700;
    }

    h2 {
        margin: 0;
        font-size: 5vmin;
        line-height:5vmin; 
    }
    
    .space {
        display: inline-block;
        width: 0.5rem;
        height: 1rem;
    }

    .button {
        display: inline-flex;
        justify-content: center;
        background: var(--primary-green);
        color: black;
        border-radius: 2.5px;
        padding: 0.5rem;
        transition: ease 0.25s;
        cursor: pointer;
        user-select: none;        
        margin:0;
        line-height: 1rem;
    }
    
    .button:hover {
        transform: translateX(-0.25em);
    }

    .button:active {
        transform: scale(0.98);
    }

    .button-box {
        display:flex;
        justify-content:end;
        flex-grow: 4;
        gap:1.5rem;
        font-size:1.25rem;
    }
</style>
