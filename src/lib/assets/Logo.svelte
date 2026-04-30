<script>
    let { width = "8rem" } = $props();
</script>

<svg
    {width}
    viewBox="0 0 220 36"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
>
    <!-- Recovr icon -->
    <path
        d="M18.3926 9.9317C21.0185 9.9317 23.5368 8.89216 25.3937 7.04172C27.2505 5.19129 28.2939 2.68152 28.2942 0.0644531H8.49219C8.49219 2.68141 9.53527 5.19118 11.3920 7.04165C13.2486 8.89212 15.7669 9.9317 18.3926 9.9317Z"
        fill="var(--builder-accent, #586D39)"
    />
    <path
        d="M21.0648 34.8431C22.5255 33.3873 22.5256 31.0268 21.0648 29.5709C19.604 28.115 17.2356 28.115 15.7748 29.5709C14.3141 31.0268 14.3141 33.3873 15.7748 34.8431C17.2356 36.299 19.604 36.299 21.0648 34.8431Z"
        fill="var(--builder-accent, #586D39)"
    />
    <path
        d="M18.3333 27.246C22.6134 27.2457 26.7181 25.5509 29.7445 22.5345C32.7709 19.518 34.4711 15.4269 34.4711 11.1611H2.19434C2.19434 15.4271 3.89469 19.5184 6.92133 22.5349C9.94797 25.5514 14.053 27.246 18.3333 27.246Z"
        fill="var(--builder-accent, #586D39)"
    />

    <!-- Wordmark: "recovr Builder" -->
    <text
        x="48"
        y="25"
        font-family="ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, sans-serif"
        font-size="22"
        letter-spacing="-0.5"
    >
        <tspan font-weight="600" fill="var(--builder-text-primary, white)">recovr</tspan>
        <tspan font-weight="300" fill="var(--builder-text-secondary, #999999)" dx="6">Builder</tspan>
    </text>
</svg>
