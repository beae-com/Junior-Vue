<script setup>
</script>
<template>
  <div class="divide-y w-1/2 mx-auto border rounded shadow flex flex-col justify-center gap-3 mt-10 p-3">
    <div>
      <h1 class="text-3xl font-bold">Beae Junior VueJS Test</h1>
      <div class="text-2xl content-auto text-red-500">
        Source dự án đã cài sẵn các thư viện cần thiết: Tailwind CSS, Vue, Vite
      </div>
    </div>
    <div>
      <h2 class="text-2xl">Đề bài:</h2>
      <p>- Thời gian làm bài: 30 phút</p>
      <p>
        - Yêu cầu ứng viên xây dựng một ứng dụng Vue đơn giản có các chức năng
        sau:
      </p>
    </div>
    <div>
      <h2 class="text-2xl">Chức năng</h2>
      <h3 class="text-xl">1. Danh sách công việc (To-do List)</h3>
      <ul>
        <li>
          - Tạo một component TodoList để hiển thị danh sách các công việc.
        </li>
        <li>
          - Mỗi công việc bao gồm: tên công việc, và trạng thái (hoàn thành/chưa
          hoàn thành).
        </li>
        <li>
          - Cho phép chỉnh sửa tên công việc khi trạng thái của nó là chưa hoàn thành (nếu đã hoàn thành thì không cho chỉnh sửa nữa).
        </li>
        <li>- Thêm một công việc mới vào danh sách.</li>
        <li>- Xóa một công việc ra khỏi danh sách.</li>
        <li>- Đánh dấu một công việc là hoàn thành hoặc chưa hoàn thành.</li>
      </ul>
      <h3 class="text-xl">2. Component con</h3>
      <ul>
        <li>
          - Sử dụng một component con để hiển thị từng mục công việc (TodoItem),
          với props truyền xuống từ component cha (TodoList).
        </li>
      </ul>
      <h3 class="text-cl">3. Local storage (Bonus - không bắt buộc)</h3>
      <ul>
        <li>
          - Lưu trạng thái của danh sách công việc vào localStorage để khi
          reload trang vẫn giữ lại được danh sách công việc đã thêm.
        </li>
      </ul>
    </div>
    <div>
      <h2 class="text-2xl">Yêu cầu:</h2>
      <ul>
        <li>- Sử dụng Vue.js phiên bản 3.</li>
        <li>- Sử dụng TailwindCss để style cho components.</li>
      </ul>
    </div>
    <div>
      <h2 class="text-2xl">Các tiêu chí đánh giá:</h2>
      <ul>
        <li>
          - Kiến thức cơ bản về VueJS: Sử dụng đúng cách các directive như
          v-for, v-bind, v-model, và v-on.
        </li>
        <li>
          - Quản lý state: Kiểm tra cách quản lý dữ liệu trong component và khả
          năng tương tá lic giữa component cha - con.
        </li>
        <li>
          - Clean Code: Cách cấu trúc code, đặt tên biến, và cách giải quyết vấn
          đề.
        </li>
        <li>
          - Bonus: Nếu có thêm phần lưu dữ liệu vào localStorage là một điểm
          cộng.
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
</style>
