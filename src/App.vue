<script setup lang="ts">
  import Navigation from './components/Navigation.vue'
</script>

<template>
<div className="min-h-screen bg-gray-800">
  <Navigation />
  <section className="pt-24 pb-16 px-6">
    <div className="max-w-6xl mx-auto">
      <div className="relative">
        <div className="absolute inset-0 flex items-center justify-center opacity-5">
          <div className="text-[30rem] bg-gradient-to-r from-cyan-400 via-teal-500 to-fuchsia-600
           bg-clip-text text-transparent ">
            ARVI 
          </div>
        </div>

        <div className="relative z-10 text-center py-20">
          <h1 className="text-6xl md:text-8xl font-black mb-6 bg-gradient-to-r from-cyan-400 via-teal-500 to-fuchsia-600
           bg-clip-text text-transparent animate-in fade-in slide-in-from-bottom-8 duration-1000">
            Hello, I'm Aldwin Rich
          </h1>
        <p className="text-2xl md:text-3xl text-gray-200 mb-8 animate-in fade-in slide-in-from-bottom-8 duration-1000 delay-300">
            Full Stack Developer
        </p>
          <div className="flex flex-col sm:flex-row gap-4 justify-center animate-in fade-in slide-in-from-bottom-8 duration-1000 delay-500">
            <Link to="/use-case">
              <Button size="lg" className="text-lg px-8 py-4">
                View My Work
              </Button>
            </Link>
            <Link to="/contact">
              <Button variant="outline" size="lg" className="text-lg px-8 py-4">
                Get In Touch
              </Button>
            </Link>
          </div>
        </div>
      </div>
    </div>
  </section>

  
  <section className="py-20 px-6">
    <div className="max-w-4xl mx-auto">
      <Card className="backdrop-blur-sm bg-white/70 border-0 shadow-2xl">
        <CardContent className="p-12">
          <h2 className="text-4xl font-bold text-center mb-8 bg-gradient-to-r from-blue-600 to-purple-600 bg-clip-text text-transparent">
            About Me
          </h2>
          <div className="grid md:grid-cols-2 gap-12 items-center">
            <div>
              <p className="text-lg text-gray-700 leading-relaxed mb-6">
              </p>
              <p className="text-lg text-gray-700 leading-relaxed mb-6">
              </p>
              <div className="flex flex-wrap gap-3">
                <span className="px-4 py-2 bg-blue-100 text-blue-800 rounded-full text-sm font-medium">
                  React
                </span>
                <span className="px-4 py-2 bg-green-100 text-green-800 rounded-full text-sm font-medium">
                  Node.js
                </span>
                <span className="px-4 py-2 bg-purple-100 text-purple-800 rounded-full text-sm font-medium">
                  TypeScript
                </span>
                <span className="px-4 py-2 bg-orange-100 text-orange-800 rounded-full text-sm font-medium">
                  AWS
                </span>
              </div>
            </div>
            <div className="text-center">
              <div className="w-64 h-64 mx-auto bg-gradient-to-br from-blue-400 to-purple-500 rounded-full flex items-center justify-center text-white text-6xl font-bold shadow-2xl">
                A
              </div>
              <p className="mt-4 text-gray-600">
                Ready to bring your ideas to life
              </p>
            </div>
          </div>
        </CardContent>
      </Card>
    </div>
  </section>
</div>
        
</template>

<style scoped>

</style>
