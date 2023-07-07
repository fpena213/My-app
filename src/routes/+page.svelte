<script>
    import { Glitter } from '@michaelb21/npmtest'
    import { goto } from '$app/navigation'
    import { LoginBox } from '@michaelb21/npmtestoauth'

    console.log(import.meta.env.VITE_GITHUB_CLIENT_ID)
</script>

<LoginBox form data/>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
