<script>
export default {
  data() {
    return {
      activeTab: 1,
      tech: [
        {
          id: 1,
          name: 'Facebook',
          imageUrl: 'https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/facebook-round-color-icon.png',
          status: 'Phan Hoàng Gia Huy',
          link: 'https://www.facebook.com/GiaHuyPH'
        },
        {
          id: 2,
          name: 'Instagram',
          imageUrl: 'src="https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/ig-instagram-icon.png"',
          status: 'phghuy2007',
          link: 'https://www.instagram.com/phghuy2007/'
        },
        {
          id: 3,
          name: 'Zalo',
          imageUrl: 'https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/zalo-icon.png',
          status: '0974705778',
        },
        {
          id: 4,
          name: 'Discord',
          imageUrl: 'https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/discord-round-color-icon.png',
          status: 'phghuy',
          link: 'https://discord.com/users/547053907440959499'
        },
        {
          id: 5,
          name: 'Steam',
          imageUrl: 'https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Steam_icon_logo.svg/2048px-Steam_icon_logo.svg.png',
          status: 'phghuy',
          link: 'https://steamcommunity.com/profiles/765611993791914989'
        },
        {
          id: 6,
          name: 'Github',
          imageUrl: 'https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/github-icon.png',
          status: 'PHGHuy2007',
          link: 'https://github.com/PHGHuy2007'
        },
        {
          id: 7,
          name: 'Locket',
          imageUrl: 'https://ineqe.com/wp-content/uploads/2022/02/locket_app_icon-1024x1024.png',
          status: 'phghuy',
          link: 'https://locket.camera/invites/buFB4mYtiEO8Kwza7p0RHbjPIMp1e6e8c6bc68ad4365?type=Link&variant=1002&social_title=Th%C3%AAm+t%C3%B4i+tr%C3%AAn+Locket+%F0%9F%92%9B&social_desc=T%C3%B4i+mu%E1%BB%91n+th%C3%AAm+b%E1%BA%A1n+v%C3%A0o+M%C3%A0n+h%C3%ACnh+ch%C3%ADnh+c%E1%BB%A7a+t%C3%B4i+qua+Locket.+Ch%E1%BA%A1m+v%C3%A0o+li%C3%AAn+k%E1%BA%BFt+%C4%91%E1%BB%83+ch%E1%BA%A5p+nh%E1%BA%ADn.&social_img=https://firebasestorage.googleapis.com:443/v0/b/locket-img/o/users%252FbuFB4mYtiEO8Kwza7p0RHbjPIMp1%252Fpublic%252Finvite_link_previews%252F1725037283.5904322.webp?alt%3Dmedia%26token%3D071f79af-c109-46bb-ae13-64e6bedb5065&lang=vi'
        },
        {
          id: 8,
          name: 'Tiktok',
          imageUrl: 'https://p16-tiktokcdn-com.akamaized.net/obj/tiktok-obj/32f2ab89bf0d9acee8ff3021890559a7.png',
          status: 'Beginner',
          link: 'https://www.tiktok.com/@phghuy2k7'
        },
        {
          id: 9,
          name: 'Vietcombank',
          imageUrl: 'https://i.imgur.com/ljqYXCE.png',
          status: '1033238721',
        },
        {
          id: 10,
          name: 'Valorant',
          imageUrl: 'https://i.imgur.com/2SV8Yfq.png',
          status: 'PHGHuy#VN2',
        },
        {
          id: 11,
          name: 'LiênQuân',
          imageUrl: 'https://i.imgur.com/r6K5bRP.png',
          status: 'Huychaidim',
        },
        {
          id: 12,
          name: 'FreeFire',
          imageUrl: 'https://i.imgur.com/kLg3bVO.png',
          status: '?',
        }
      ],
      tools: [
        {
          id: 1,
          name: 'Git',
          imageUrl: 'https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png',
          status: 'Version Control',
          link: 'https://git-scm.com/'
        },
        {
          id: 2,
          name: 'GitHub',
          imageUrl: 'https://cdn-icons-png.flaticon.com/512/25/25231.png',
          status: 'Git Hosting',
          link: 'https://github.com/'
        },
        {
          id: 3,
          name: 'NPM',
          imageUrl: 'https://cdn.iconscout.com/icon/free/png-256/free-npm-3-1175132.png',
          status: 'Package Manager',
          link: 'https://www.npmjs.com/'
        },
        {
          id: 4,
          name: 'MySQL',
          imageUrl: 'https://cdn-icons-png.flaticon.com/512/5968/5968313.png',
          status: 'Database',
          link: 'https://www.mysql.com/'
        },
      ]
    };
  },
  methods: {
    openLink(url) {
      if (url) {
        // Mở link ở một tab mới
        window.open(url, '_blank');
        
        // Nếu bạn muốn dùng vue-router để chuyển trang nội bộ thì dùng dòng dưới thay thế:
        // this.$router.push(url);
      }
    }
  }
}
</script>

<template>
  <div class="bg-[#1e1e1f] px-5 py-5 md:px-12 md:py-10 text-left border border-[#383838] rounded-3xl text-amber-50 mx-3 mb-5">
    <article data-page="about">

      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          About Me &nbsp;
          <div class="h-[1px] w-32 bg-amber-200 md:w-96 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
        </div>
      </header>

      <section class="text-sm md:text-lg text-justify flex flex-col gap-4 md:flex-row md:gap-8 md:justify-left md:items-center">
        <div class="flex justify-center">
          <img class="w-9/12 rounded-full mb-3 fadein-up"
            src="https://i1.sndcdn.com/avatars-000214125831-5q6tdw-t500x500.jpg" alt="Foto">
        </div>
        <div class="md:w-7/12">
          <p class="mb-3 md:mb-7 fadein-left fadeins-1">
            &nbsp; &nbsp; &nbsp; Xin chào mọi người, mình tên là Phan Hoàng Gia Huy, hiện đang là sinh viên lập trình tại FPT Aptech. 
            Mình đến từ Hồng Lĩnh, Hà Tĩnh và hiện đang sinh sống, học tập tại Cầu Diễn, Hà Nội. Mình là người độc thân, vui tính, 
            dễ gần, thích chơi game, đá bóng, chụp ảnh, ăn uống và ca hát cùng bạn bè.
          </p>
          <p class="mb-3 fadein-left fadeins-2">
            &nbsp; &nbsp; &nbsp; Hiện tại, ngoài việc học, mình còn làm freelance chụp ảnh – một công việc mình rất yêu thích 
            vì vừa có thêm thu nhập vừa được thỏa sức sáng tạo. Mình cảm thấy khá hài lòng với cuộc sống hiện tại 
            và luôn cố gắng phát triển bản thân hơn mỗi ngày. Dưới đây là một số trang mạng xã hội của mình, 
            mọi người ghé qua ủng hộ và kết nối với mình nhé!
          </p>
        </div>
      </section>

    </article>
  </div>

  <div class="px-5 py-5 md:px-12 md:py-10 text-left text-amber-50 mx-3">
    <article data-page="about">
      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          <div class="h-[1px] w-10 bg-amber-200 md:w-20 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
          &nbsp; Skills
        </div>
      </header>
      <section>
        <div>
          <ul class="flex flex-wrap text-sm font-medium text-center text-gray-500 dark:text-gray-400 mb-5">
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 1 }" @click="activeTab = 1">Network, Game</button>
            </li>
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 2 }" @click="activeTab = 2">Skills</button>
            </li>
          </ul>
        </div>
        
        <div v-show="activeTab === 1">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in tech" :key="item.id">
              <div
                @click="openLink(item.link)"
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img :alt="item.name" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]"
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div v-show="activeTab === 2">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in tools" :key="item.id">
              <div
                @click="openLink(item.link)"
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img :alt="item.name" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]"
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        
      </section>
    </article>
  </div>
</template>

<style>
.fadein-left {
  opacity: 0;
  animation: fadeInLeft 0.5s ease-out forwards;
}

@keyframes fadeInLeft {
  0% {
    opacity: 0;
    transform: translateX(100%);
  }

  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

.fadeins-1 {
  animation-delay: 500ms;
}

.fadeins-2 {
  animation-delay: 800ms;
}

.img-tech,
.tech {
  transition: transform 0.3s ease;
}

.item-tech:hover .img-tech {
  transform: scale(1.3);
}

.item-tech:hover .tech {
  transform: translateY(-12px);
}

.item-tech:hover .status-tech {
  opacity: 1;
}
</style>