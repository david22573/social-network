<template>
    <div class="max-w-7xl mx-auto grid grid-cols-2 gap-4">
        <div class="main-left">
            <div class="p-12 bg-white border border-gray-200 rounded-lg">
                <h1 class="mb-6 text-xl font-bold">Log in</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis hic consequuntur, mollitia natus repudiandae quos deleniti laudantium aliquam officiis sint suscipit blanditiis expedita repellat eligendi ipsa nostrum architecto quas quae.</p>
                <p class="font-bold py-12">
                    Don't have an account? <RouterLink :to="{'name': 'signup'}" class="underline">Click here</RouterLink> to log create one!
                </p>
            </div>
        </div>
        <div class="main-right">
            <div class="p-12 bg-white border border-gray-200 rounded-lg">
                <form class="space-y-6">
                    <div>
                        <label for="email">E-mail</label>
                        <input
                            type="email"
                            placeholder="Your e-mail address"
                            class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg"    
                        />
                    </div>
                    <div>
                        <label for="email">Password</label>
                        <input
                            type="password"
                            placeholder="Your password"
                            class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg"    
                        />
                    </div>
                    <div>
                        <button class="py-4 px-6 bg-purple-600 text-white rounded-lg">Log In</button>
                    </div>
                </form>
            </div>
        </div>
    </div>
</template>